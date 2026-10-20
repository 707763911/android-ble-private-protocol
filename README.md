# Android BLE Private Protocol

Android BLE GATT 连接与私有协议通用框架实现。协议字段为脱敏合成数据，不包含企业真实私有协议。

## 功能
- BLE 扫描与 GATT 连接【能做到稳定被发现和连接！】
- 服务/特征发现
- 协议帧编解码接口
- 分包/粘包处理与校验
- 超时重试、断线重连
- 收发日志追踪

## 技术栈
Kotlin、Android BLE API、Coroutines / Flow

## 快速开始
1. Android Studio 打开项目
2. 准备一台 BLE 从设备或使用模拟数据
3. 发起扫描、连接与收发

## 安全与合规
- 协议字段为脱敏合成数据
- 不公开企业真实协议细节
- 不包含客户设备信息与密钥

## License
MIT
