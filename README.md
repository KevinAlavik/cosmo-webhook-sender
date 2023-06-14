# Cosmo Webhook Sender
Simple webhook sender using:
- [https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/webhook.cr](https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/webhook.cr)
- [https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/http.cr](https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/http.cr)
- [https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/file.cr](https://github.com/cosmo-lang/cosmo/blob/master/src/cosmo/runtime/intrinsic/lib/file.cr)

(i made the **File::read()** function and **DiscordWebhook::send()**)

## Usage
First you need to install cosmo follow the instructions [here](https://github.com/cosmo-lang/cosmo/tree/master#installation)
Then just run these commmands:
```bash
git clone https://github.com/KevinAlavik/cosmo-webhook-sender/
cd cosmo-webhook-sender
cosmo main.cos
```
Now visit [127.0.0.1:8080](http://127.0.0.1:8080) (This website is only on **your** network, **no one else can access it**)
