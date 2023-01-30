VRChatのアバターに使用できる簡易アイテムの出し入れモジュールです。

Avatarの直下に入れるだけで簡単に設定することができます。
 - 利用にはModular Avatar が必要です。

![image](https://user-images.githubusercontent.com/34181574/215449756-146f98e3-2ce0-420e-af20-e22070a0bb5a.png)


### Grip
この配下に出し入れするメッシュを入れてください。
![image](https://user-images.githubusercontent.com/34181574/215450054-b4dce156-c8d0-4dcd-84ad-65bb4ab31584.png)

ProxyTarget1
ProxyTarget2

アイテムの出現位置となります。
刀や銃などを「持つ」位置と「しまう」位置等で設定可能です。
位置調整をする際はGripのParentConstraintで調整するProxyのほうを1、そうでないほうを0にしてそれぞのProxyの位置を調整してください。

なおMA Bone Proxyが設定されており、どのボーンに追従するかを設定する必要があります。
右手に持たせた場合はアバターの右手のボーンに設定してください。

![image](https://user-images.githubusercontent.com/34181574/215450502-ea601f71-c24c-43de-a390-127f6974897f.png)
