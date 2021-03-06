[mirai-core](../../index.md) / [net.mamoe.mirai.utils](../index.md) / [SingleFileLogger](./index.md)

# SingleFileLogger

`class SingleFileLogger : `[`PlatformLogger`](../-platform-logger/index.md)

将日志写入('append')到特定文件.

**See Also**

[PlatformLogger](../-platform-logger/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | 将日志写入('append')到特定文件.`SingleFileLogger(identity: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, file: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)` = File("$identity-$currentDate.log"))` |

### Extension Functions

| Name | Summary |
|---|---|
| [debug](../debug.md) | `fun `[`MiraiLogger`](../-mirai-logger/index.md)`.debug(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.debug(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [error](../error.md) | `fun `[`MiraiLogger`](../-mirai-logger/index.md)`.error(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.error(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [info](../info.md) | `fun `[`MiraiLogger`](../-mirai-logger/index.md)`.info(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.info(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [verbose](../verbose.md) | `fun `[`MiraiLogger`](../-mirai-logger/index.md)`.verbose(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.verbose(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [warning](../warning.md) | `fun `[`MiraiLogger`](../-mirai-logger/index.md)`.warning(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.warning(lazyMessage: () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [withSwitch](../with-switch.md) | 给这个 logger 添加一个开关, 用于控制是否记录 log`fun `[`MiraiLogger`](../-mirai-logger/index.md)`.withSwitch(default: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): `[`MiraiLoggerWithSwitch`](../-mirai-logger-with-switch/index.md) |
