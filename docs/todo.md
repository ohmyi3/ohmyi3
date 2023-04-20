# Todo



## Trim Uvicore

uvicore needs to be trimmed down
dont need
  aiohttp
  MarkupSafe ??
  multidict??? - thought I got rid of that?


```
    ~  pip install ohmyi3                                                                                                                                                                                                             ✔
Collecting ohmyi3
  Downloading ohmyi3-0.1.1-py3-none-any.whl (1.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 1.9 MB/s eta 0:00:00
Collecting jinja2<3.2.0,>=3.1.0 (from ohmyi3)
  Downloading Jinja2-3.1.2-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.1/133.1 kB 3.8 MB/s eta 0:00:00
Collecting uvicore==0.1.25 (from ohmyi3)
  Downloading uvicore-0.1.25-py3-none-any.whl (337 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 337.5/337.5 kB 3.9 MB/s eta 0:00:00
Collecting aiohttp<3.8.0,>=3.7.0 (from uvicore==0.1.25->ohmyi3)
  Downloading aiohttp-3.7.4.post0.tar.gz (1.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 3.7 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting anyio<3.3.0,>=3.2.0 (from uvicore==0.1.25->ohmyi3)
  Downloading anyio-3.2.1-py3-none-any.whl (75 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 75.4/75.4 kB 3.8 MB/s eta 0:00:00
Collecting argon2-cffi<20.2.0,>=20.1.0 (from uvicore==0.1.25->ohmyi3)
  Using cached argon2_cffi-20.1.0-cp35-abi3-manylinux1_x86_64.whl (97 kB)
Collecting colored<1.5.0,>=1.4.0 (from uvicore==0.1.25->ohmyi3)
  Downloading colored-1.4.4.tar.gz (36 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting cryptography<3.5.0,>=3.4.0 (from uvicore==0.1.25->ohmyi3)
  Downloading cryptography-3.4.8-cp36-abi3-manylinux_2_24_x86_64.whl (3.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.0/3.0 MB 5.5 MB/s eta 0:00:00
Collecting environs<9.4.0,>=9.3.0 (from uvicore==0.1.25->ohmyi3)
  Downloading environs-9.3.5-py2.py3-none-any.whl (12 kB)
Collecting httpx<0.20.0,>=0.19.0 (from uvicore==0.1.25->ohmyi3)
  Downloading httpx-0.19.0-py3-none-any.whl (77 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.3/77.3 kB 8.3 MB/s eta 0:00:00
Collecting merge-args<0.2.0,>=0.1.0 (from uvicore==0.1.25->ohmyi3)
  Downloading merge_args-0.1.5-py2.py3-none-any.whl (6.0 kB)
Collecting prettyprinter<0.19.0,>=0.18.0 (from uvicore==0.1.25->ohmyi3)
  Using cached prettyprinter-0.18.0-py2.py3-none-any.whl (48 kB)
Collecting MarkupSafe>=2.0 (from jinja2<3.2.0,>=3.1.0->ohmyi3)
  Downloading MarkupSafe-2.1.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (25 kB)
Collecting attrs>=17.3.0 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Downloading attrs-23.1.0-py3-none-any.whl (61 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.2/61.2 kB 8.2 MB/s eta 0:00:00
Collecting chardet<5.0,>=2.0 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Using cached chardet-4.0.0-py2.py3-none-any.whl (178 kB)
Collecting multidict<7.0,>=4.5 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Downloading multidict-6.0.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (114 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 114.5/114.5 kB 12.3 MB/s eta 0:00:00
Collecting async-timeout<4.0,>=3.0 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Using cached async_timeout-3.0.1-py3-none-any.whl (8.2 kB)
Collecting yarl<2.0,>=1.0 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Downloading yarl-1.8.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (264 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 264.0/264.0 kB 12.7 MB/s eta 0:00:00
Collecting typing-extensions>=3.6.5 (from aiohttp<3.8.0,>=3.7.0->uvicore==0.1.25->ohmyi3)
  Using cached typing_extensions-4.5.0-py3-none-any.whl (27 kB)
Collecting idna>=2.8 (from anyio<3.3.0,>=3.2.0->uvicore==0.1.25->ohmyi3)
  Using cached idna-3.4-py3-none-any.whl (61 kB)
Collecting sniffio>=1.1 (from anyio<3.3.0,>=3.2.0->uvicore==0.1.25->ohmyi3)
  Downloading sniffio-1.3.0-py3-none-any.whl (10 kB)
Collecting cffi>=1.0.0 (from argon2-cffi<20.2.0,>=20.1.0->uvicore==0.1.25->ohmyi3)
  Using cached cffi-1.15.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (441 kB)
Collecting six (from argon2-cffi<20.2.0,>=20.1.0->uvicore==0.1.25->ohmyi3)
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting marshmallow>=3.0.0 (from environs<9.4.0,>=9.3.0->uvicore==0.1.25->ohmyi3)
  Downloading marshmallow-3.19.0-py3-none-any.whl (49 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 49.1/49.1 kB 2.9 MB/s eta 0:00:00
Collecting python-dotenv (from environs<9.4.0,>=9.3.0->uvicore==0.1.25->ohmyi3)
  Downloading python_dotenv-1.0.0-py3-none-any.whl (19 kB)
Collecting certifi (from httpx<0.20.0,>=0.19.0->uvicore==0.1.25->ohmyi3)
  Downloading certifi-2022.12.7-py3-none-any.whl (155 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 155.3/155.3 kB 14.5 MB/s eta 0:00:00
Collecting charset-normalizer (from httpx<0.20.0,>=0.19.0->uvicore==0.1.25->ohmyi3)
  Downloading charset_normalizer-3.1.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (199 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.3/199.3 kB 8.6 MB/s eta 0:00:00
Collecting rfc3986[idna2008]<2,>=1.3 (from httpx<0.20.0,>=0.19.0->uvicore==0.1.25->ohmyi3)
  Downloading rfc3986-1.5.0-py2.py3-none-any.whl (31 kB)
Collecting httpcore<0.14.0,>=0.13.3 (from httpx<0.20.0,>=0.19.0->uvicore==0.1.25->ohmyi3)
  Downloading httpcore-0.13.7-py3-none-any.whl (58 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 58.8/58.8 kB 4.7 MB/s eta 0:00:00
Collecting Pygments>=2.2.0 (from prettyprinter<0.19.0,>=0.18.0->uvicore==0.1.25->ohmyi3)
  Downloading Pygments-2.15.0-py3-none-any.whl (1.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 5.4 MB/s eta 0:00:00
Collecting colorful>=0.4.0 (from prettyprinter<0.19.0,>=0.18.0->uvicore==0.1.25->ohmyi3)
  Downloading colorful-0.5.5-py2.py3-none-any.whl (201 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 201.4/201.4 kB 4.6 MB/s eta 0:00:00
Collecting pycparser (from cffi>=1.0.0->argon2-cffi<20.2.0,>=20.1.0->uvicore==0.1.25->ohmyi3)
  Using cached pycparser-2.21-py2.py3-none-any.whl (118 kB)
Collecting h11<0.13,>=0.11 (from httpcore<0.14.0,>=0.13.3->httpx<0.20.0,>=0.19.0->uvicore==0.1.25->ohmyi3)
  Downloading h11-0.12.0-py3-none-any.whl (54 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 54.9/54.9 kB 5.4 MB/s eta 0:00:00
Collecting packaging>=17.0 (from marshmallow>=3.0.0->environs<9.4.0,>=9.3.0->uvicore==0.1.25->ohmyi3)
  Using cached packaging-23.1-py3-none-any.whl (48 kB)
Building wheels for collected packages: aiohttp, colored
  Building wheel for aiohttp (pyproject.toml) ... done
  Created wheel for aiohttp: filename=aiohttp-3.7.4.post0-cp310-cp310-linux_x86_64.whl size=1387330 sha256=eae71624d133666104b890a586f328af1c2f3f82ecc6a56807b83b12ed03c4ac
  Stored in directory: /home/mreschke/.cache/pip/wheels/fc/84/e0/52113c57eb9b09b6b187a0f369eaad6fc7fc64bb7247c83b89
  Building wheel for colored (pyproject.toml) ... done
  Created wheel for colored: filename=colored-1.4.4-py3-none-any.whl size=14249 sha256=11bdfb55715eb403fc01ff543714fb9f16432c77ade5ed0c9af636105cf2f0c0
  Stored in directory: /home/mreschke/.cache/pip/wheels/e7/c3/07/fabb0941ff5df7a487d43a67081273045536cc96d4d0e816b4
Successfully built aiohttp colored
Installing collected packages: rfc3986, merge-args, colorful, colored, typing-extensions, sniffio, six, python-dotenv, Pygments, pycparser, packaging, multidict, MarkupSafe, idna, h11, charset-normalizer, chardet, certifi, attrs, async-timeout, yarl, prettyprinter, marshmallow, jinja2, cffi, anyio, httpcore, environs, cryptography, argon2-cffi, aiohttp, httpx, uvicore, ohmyi3
Successfully installed MarkupSafe-2.1.2 Pygments-2.15.0 aiohttp-3.7.4.post0 anyio-3.2.1 argon2-cffi-20.1.0 async-timeout-3.0.1 attrs-23.1.0 certifi-2022.12.7 cffi-1.15.1 chardet-4.0.0 charset-normalizer-3.1.0 colored-1.4.4 colorful-0.5.5 cryptography-3.4.8 environs-9.3.5 h11-0.12.0 httpcore-0.13.7 httpx-0.19.0 idna-3.4 jinja2-3.1.2 marshmallow-3.19.0 merge-args-0.1.5 multidict-6.0.4 ohmyi3-0.1.1 packaging-23.1 prettyprinter-0.18.0 pycparser-2.21 python-dotenv-1.0.0 rfc3986-1.5.0 six-1.16.0 sniffio-1.3.0 typing-extensions-4.5.0 uvicore-0.1.25 yarl-1.8.2
```
