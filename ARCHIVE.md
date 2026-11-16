# 归档说明

## 封存日期

2026-11-16

## 暂停原因

本轮停止推进，直接原因是：

> 兴趣不强 + 体力消耗大（未区分 A/B/C）

## ## 最小恢复动作

1. `git clone https://github.com/lcr3111696/quant-lab-01.git`

2. 核对依赖版本（本机已装，不必重装）：

   `D:\Anaconda3\python.exe -c "import akshare,pandas,numpy,matplotlib;print(akshare.__version__,pandas.__version__,numpy.__version__,matplotlib.__version__)"`

   预期 `1.20.35 2.2.3 2.1.3 3.10.0`，与 `requirements.txt` 对照。

   只有在**换了机器**时才执行 `pip install -r requirements.txt`。

3. 先读 README 的「目标 / 方法 / 失败点」，确认基线 `v0.1`（M1 结项版本）

4. 复现数据`python pull_50.py`，重新生成 `hs300_50_daily.csv`

5. 继续未完成的一步：T3.3 分层回测`layers.py`），对照 README 里的 IC 结果

   —— 只有 15 分钟时，做完第 1、2、3 步即可恢复上下文，不必跑数据

## ## 封存日

2026-11-16

## 复查日（做去留判断）

2027-01-18