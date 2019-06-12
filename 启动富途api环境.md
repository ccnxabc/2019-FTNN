首先pip install futu-api安装futu-api

anaconda 原装的numpy可能有问题与futu-api冲突，需要pip uninstall numpy，再pip install numpy

在dos下，进入FutuOpenD目录输入:D:\\FutuOpenD_1.07_Windows\>FutuOpenD.exe
-login_account=65xxxx -login_pwd=xxx -lang=en

![](media/a2c10a3326753b98dbebddd8ba0721d8.png)

![](media/26992755f5c3e49ce3aa45f3e763834d.png)

输入手机的验证码 input_phone_verify_code -code=xxx

![](media/392fde6b7a5a4fb5d16b03eb0a2189b7.png)

![](media/068c7973ae17f4a62c035ceb386e5e6f.png)

2019.06.11
#当futu PC终端异常时，API行情也会异常；必须重启PC终端

#2019-06-12 16:14:49,177 [open_context_base.py] _socket_reconnect_and_wait_ready:208: Start connecting: host=127.0.0.1; port=11111;

#2019-06-12 16:14:49,179 [open_context_base.py] on_connected:290: Connected : conn_id=1;

#2019-06-12 16:14:49,182 [open_context_base.py] _handle_init_connect:379: InitConnect ok: conn_id=1; info={'server_version': 107, 'login_user_id': 657802, 'conn_id': 12944249952739031304, 'conn_key': '0279E01CC037A34D', 'keep_alive_interval': 10};

#(-1, 'Unknown stock 02189 02189')-----对以下代码无法识别，结果API接口也出现报错
