# 🚀 Crypto High-Frequency Quant Terminal

An independent, high-performance cryptocurrency quantitative trading system built from scratch.

## 🌟 Core Features
- **Asyncio & WebSocket Architecture**: Ultra-low latency data streaming.
- **Tick-Level Order Flow Imbalance (OFI)**: Real-time tracking of micro-trends.
- **Anti-Spoofing Mechanism**: Detects fake order book walls to avoid liquidation traps.
- **Dynamic ATR Trailing Stop**: Automatically moves stop-loss to breakeven to protect capital.
- **L1/L2/L3 Circuit Breaker**: Multi-level risk control for extreme market conditions.

---

# 🚀 加密货币高频量化交易终端

纯 Python 手搓的高并发量化系统，主打微观盘口风控。

## 🌟 核心优势
- **底层架构**：基于 `asyncio` 异步高并发与 WebSocket 实时流，告别延迟。
- **微观订单流 (OFI)**：毫秒级抓取真实买卖盘，看穿主力砸盘与扫单。
- **防假托单**：精准识别诱多/诱空假挂单，自带一票否决机制。
- **ATR 动态保本**：利润跑出后自动推高止损，实现零风险博弈。
- **多级熔断**：L1-L3 风控机制，遇到极端插针自动平仓锁死。

*(注：核心策略代码已加密，此处仅作架构展示)*