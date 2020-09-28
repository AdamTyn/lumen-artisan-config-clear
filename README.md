# lumen-artisan-config-clear

移植Laravel的 `php artisan config:clear` [清除配置缓存文件]指令到Lumen

# Usage

在 **'app/commands/kernel.php'** 中注册指令：

```
protected $commands = [
	\AdamTyn\Lumen\Artisan\ConfigClearCommand::class
];
```
