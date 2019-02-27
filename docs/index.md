---
layout: default_1
---
# Description
In this project, we conducted a comprehensive study on emerging residential IP proxy as a service (RPaaS), between May 2017 and March 2018. Our study identified lots of interesting findings and answered several important questions around RPaaS. 
You can refer to [our paper](https://mixianghang.github.io/pubs/rpaas.pdf) (published on IEEE S&P 2019) and [my blog article](https://medium.com/@xianghangmi/resident-evil-understanding-residential-ip-proxy-as-a-dark-service-dea9010a0e29?sk=1b84f109431dfd92a0c73ec101b21289) for more information. Here, we will not go through those details, but  focus on datasets and sourcecode, which may facilitage future research.

To cite our work, please use the following bibtext.
```bibtex
@inproceedings{mi2019resident,
  title={Resident Evil: Understanding Residential IP Proxy as a Dark Service},
  author={Mi, Xianghang and Liu, Ying and Feng, Xuan and Liao, Xiaojing and Liu, Baojun and Wang, XiaoFeng and Qian, Feng and Li, Zhou and Alrwais, Sumayah and Sun, Limin},
  booktitle={2019 IEEE Symposium on Security and Privacy (SP)},
  year={2019},
  organization={IEEE}
}
```

Feel free to [email me](mailto:xmi@iu.edu) :blush: for any questions. And you can also [find me on Telegram](https://t.me/mixianghang). Furthermore, **[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=TKKLW85SU99TU&currency_code=USD&source=url) will be very helpful to support my follow-up projects.**
# Data
**IP addresses captured as residential web proxies**. We infiltrated 5 RPaaS providers between July 2017 and March 2018, which captured more than 6M IPv4 addresses acting as exit nodes for our infiltration traffic. You can download those IP addresses here wherein each line denotes an unique IP address along with some important attributes, separated by Tab.
* First captured date  
  The format is Year-Month-Day (e.g., 2019-02-05).
* Last captured date  
  The format is Year-Month-Day (e.g., 2019-02-05).
* Number of distinct days when this IP address was captured  
* Providers  
  This attribute represent which providers this IP address was captured from. Provider names are concatenated by underline

# Source Code