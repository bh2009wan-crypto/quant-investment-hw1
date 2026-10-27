# 量化投资第一次作业：完整交易记录

本仓库保存主方案完整逐笔交易文件，供作业核验与复现。

[下载交易记录 ZIP](https://github.com/bh2009wan-crypto/quant-investment-hw1/raw/refs/heads/main/trades.csv.zip)

- 文件：`trades.csv.zip`，解压后得到 `trades.csv`。
- 完整记录：229,787 行数据，另含 1 行表头；17 个字段。
- CSV 大小：52,082,937 字节。
- ZIP 大小：15,775,020 字节。
- 数值、字段、行顺序和原始 CSV 字节全部保留；未截断、删行或降低数值精度。

## 使用方法

1. 下载上面的 ZIP 并解压。
2. 将 `trades.csv` 放入平台提交包解压目录的 `outputs/main/`，与 `daily.csv` 同级。
3. 代码、配置、每日净值和报告在平台提交包中；复现时按包内说明使用教师提供的原始数据。

## 校验

```text
08ec066e1511dd79b76d518216bb0d6b1acfb1a70a0cc24f81e061e3020e1f8f  trades.csv.zip
aab19af0977465c2f28395dfba2990002024ff36651d97e43e9ac3e151507c24  trades.csv
```

macOS / Linux 可用 `shasum -a 256 trades.csv.zip` 校验下载包，解压后用 `shasum -a 256 trades.csv` 校验完整交易文件。

## 字段（原始顺序）

`date, side, lot_id, code, signal_date, buy_date, units, reference_price, execution_price, amount, fee, slippage_cost, cash_delta, adv20, participation, quantity_type, hold_sessions`

本仓库仅包含本次作业生成的交易记录及说明，不包含教师原始数据、报告或其他作业材料。
