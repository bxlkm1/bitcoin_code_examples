# bitcoin_code_examples

Examples of bitcoin source

---
# testsha256.cpp

编译：

> g++ -o .\testsha256 .\testsha256.cpp -std=gnu++0x

运行：

> .\testsha256

结果：

> Data: 00154de7cabbb5822075e92c57a27ca3ef3e8be50c</br>
> SHA-256: ab7d579d497d75ab7e337212345635a4c071c249c6e8ec7532d2ea4d82290e6

---
# testhash256.cpp

编译:

> g++ -o .\testhash256 .\testhash256.cpp -std=gnu++0x

运行：

> .\testhash256

输出：

> Data: 00154de7cabbb5822075e92c57a27ca3ef3e8be50c</br>
> SHA-256 [1]: ab7d579d497d75ab7e337212345635a4c071c249c6e8ec7532d2ea4d82290e6</br>
> SHA-256 [2]: fc897c201ef5e99b2e37853e84dd041bebe6f831f462729de2af27e4ab9ea7e

---
# testbase58.cpp

编译:

> g++ -o .\testbase58 .\testbase58.cpp -std=gnu++0x

运行：

> .\testbase58

结果：

> Encode: 12weWzbq5jT7c3MHbHD2WP2uLXEUtaGLXZ</br>
> Decode: 00154de7cabbb5822075e92c57a27ca3ef3e8be50cfc897c20

---

# testbase58check

编译：

> g++ -o .\testbase58check .\testbase58check.cpp -std=gnu++0x

运行：

> .\testbase58check

结果：

> Encode: 12weWzbq5jT7c3MHbHD2WP2uLXEUtaGLXZ</br>
> Decode: 00154de7cabbb5822075e92c57a27ca3ef3e8be50c

---

# testripemd160.cpp

编译：

>  g++ -o .\testripemd160 .\testripemd160.cpp -std=gnu++0x

运行：

> .\testripemd160

结果:

> Data: 2b0995c0703c96d694f03a8987f89d387459fc359694737547a75764989c5e16</br>
> RIPEMD-160: 154de7cabbb5822075e92c57a27ca3ef3e8be5c

---

# testhash160.cpp

编译：

>  g++ -o .\testhash160 .\testhash160.cpp -std=gnu++0x

运行：

> .\testhash160

结果:

> Data: 0340a609475afa1f9a784cad0db5d5ba7dbaab2147a5d7b9bbde4d1334a0e40a5e</br>
> Hash-160: 154de7cabbb5822075e92c57a27ca3ef3e8be5c

---

# testpubkey.c.cpp

编译：

>  gcc .\testpubkey.c .\secp256k1.c -o .\testpubkey

运行：

> .\testpubkey

结果:

> Private key: 9a9a6539856be209b8ea2adbd155c0919646d108515b60b7b13d6a79f1ae5174</br>
> Public key : [X(188ac3f1c6bbbc336fdc33cb5e605ff7c3ee2d36249933b0322220a616a11fb3):Y(40a609475afa1f9a784cad0db5d5ba7dbaab2147a5d7b9bbde4d1334a0e40a5e)]</br>
> Compressed key  : 0340a609475afa1f9a784cad0db5d5ba7dbaab2147a5d7b9bbde4d1334a0e40a5e</br>
> Uncompressed key: 0440a609475afa1f9a784cad0db5d5ba7dbaab2147a5d7b9bbde4d1334a0e40a5e188ac3f1c6bbbc336fdc33cb5e605ff7c3ee2d36249933b0322220a616a11fb3

---

# testsha512.cpp

编译：

>  g++ .\testsha512.cpp -o .\testsha512

运行：

> .\testsha512

结果:

> Data: 2b0995c0703c96d694f03a8987f89d387459fc359694737547a75764989c5e16</br>
> SHA-512: f679fba58d54b19627b717d192656cf928bdeab5f201006fc219d6c56105f086baebbacc8fb5b8a83eae873a73ee0b417fdbb4098948749c410ee4166411cf3d

---

# TestKey

使用系统头文件<endian.h>

```
//  use system endian.h   //
#define HAVE_ENDIAN_H 1
#define HAVE_DECL_HTOBE16 1
#define HAVE_DECL_HTOLE16 1
#define HAVE_DECL_BE16TOH 1
#define HAVE_DECL_LE16TOH 1
#define HAVE_DECL_HTOBE32 1
#define HAVE_DECL_HTOLE32 1
#define HAVE_DECL_BE32TOH 1
#define HAVE_DECL_LE32TOH 1
#define HAVE_DECL_HTOBE64 1
#define HAVE_DECL_HTOLE64 1
#define HAVE_DECL_BE64TOH 1
#define HAVE_DECL_LE64TOH 1
////////////////////////////
```

编译：

> make

---

# Script测试

编译前需安装boost

> sudo apt install libboostX.XX-all-dev

---

# TestKey-1.1.0

增加keystore测试程序

---

# TestKey-1.2.0

增加Base58Check Encode/Decode Destination测试程序

---
# TestKey-1.3.0

增加Decode Hex Transaction测试程序

---


