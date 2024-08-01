### 该库已归档，以支持 [v2ray-worker](https://github.com/vfarid/v2ray-worker)。

### 用于创建订阅链接的 Worker 脚本

1. **脚本**：从 `dist` 目录下载脚本文件内容，并将其复制到您的 Worker 中。
2. **视频教程**：
   - [第1部分：创建带有干净 IP 的 Worker](https://youtu.be/oxYoILJ9Hgk)
   - [第2部分：将订阅链接添加到 Masuri](https://youtu.be/Pq5FWdG31Yc)
   - [Telegram 频道中的视频和描述](https://t.me/vahidgeek/72)

### 示例订阅链接：

```plaintext
https://my-worker.my-id.workers.dev/sub
```

### 添加运营商代码：

```plaintext
https://my-worker.my-id.workers.dev/sub/mci
```

### 运营商代码列表：

| 三字代码 | 运营商      |
|----------|-------------|
| afn      | Afranet     |
| apt      | Asre Telecom|
| ast      | Asiatech    |
| dbn      | Didban      |
| dtk      | Datak       |
| fnv      | Fanava      |
| hwb      | Hiweb       |
| mbt      | Mobinnet    |
| mci      | Hamrah Aval |
| mkh      | TCI         |
| mtn      | Irancell    |
| prs      | Pars Online |
| psm      | Pishgaman   |
| rsp      | Respina     |
| rtl      | RighTel     |
| sht      | Shatel      |
| ztl      | Zitel       |

### 其他示例链接：

- 带干净 IP：`https://my-worker.my-id.workers.dev/sub/1.2.3.4`
- 多个干净 IP：`https://my-worker.my-id.workers.dev/sub/1.2.3.4,9.8.7.6`
- 干净 IP 域名：`https://my-worker.my-id.workers.dev/sub/mci.ircf.space`
- 多个子域名：`https://my-worker.my-id.workers.dev/sub/mci.ircf.space,my.domain.me`
- 变量：
  - `max` 用于配置数量：`https://my-worker.my-id.workers.dev/sub?max=200`
  - `original` 用于原始配置：`https://my-worker.my-id.workers.dev/sub?original=yes`
  - `merge` 删除组合配置：`https://my-worker.my-id.workers.dev/sub?merge=no`
  - `fp` 和 `alpn` 用于指定浏览器和协议：`https://my-worker.my-id.workers.dev/sub?fp=chrome&alpn=h2,http/1.1`

### 可接受的 fp 值：

| 序号 | fp         |
|------|------------|
| 1    | chrome     |
| 2    | edge       |
| 3    | ios        |
| 4    | firefox    |
| 5    | android    |
| 6    | safari     |
| 7    | randomized |
| 8    | random     |

### 可接受的 alpn 值：

| 序号 | alpn       |
|------|------------|
| 1    | h2,http/1.1|
| 2    | h2         |
| 3    | http/1.1   |

### 配置类型：

```plaintext
https://my-worker.my-id.workers.dev/sub?type=vmess,ss,ssr,vless
```

### 限制提供商：

```plaintext
https://my-worker.my-id.workers.dev/sub?provider=mahdibland,vpei
```

### 可接受的提供商列表：

| 序号 | 提供商     |
|------|------------|
| 1    | mahdibland |
| 2    | vpei       |
| 3    | mfuu       |
| 4    | peasoft    |
| 5    | ermaozi    |
| 6    | aiboboxx   |
| 7    | pawdroid   |
| 8    | autoproxy  |
| 9    | freefq     |
