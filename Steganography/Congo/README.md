#Congo

![congo](https://user-images.githubusercontent.com/44063862/49643001-883f2480-fa4f-11e8-801b-b08e13a3e7a6.PNG)

We are given a bear image.

![inn0c3nt_b34r](https://user-images.githubusercontent.com/44063862/49642987-7c536280-fa4f-11e8-8afa-4f9abaf9625a.png)
Figure 1 Inn0c3nt_B34r

1.	strings
We try ‘strings’ it in Parrot Terminal

![image](https://user-images.githubusercontent.com/44063862/49643041-a4db5c80-fa4f-11e8-9e05-53bcb4ede22f.png)

![image](https://user-images.githubusercontent.com/44063862/49643053-aa38a700-fa4f-11e8-8c68-a937b403ea73.png)

At the bottom of strings result show .txt

2.	binwalk
We try binwalk to see is there any file other than it should.

![image](https://user-images.githubusercontent.com/44063862/49643092-c8060c00-fa4f-11e8-8c67-faccc3d0b443.png)

There is zip file

Now we extract the zip file

![image](https://user-images.githubusercontent.com/44063862/49643114-d7855500-fa4f-11e8-9b7d-ac9332a06e46.png)

![image](https://user-images.githubusercontent.com/44063862/49643127-e0762680-fa4f-11e8-85ec-e00ce3a4c739.png)

There is this file in the folder.

![image](https://user-images.githubusercontent.com/44063862/49643165-f552ba00-fa4f-11e8-8205-e7552e119bf8.png)

This is the content of the .txt file

>yvja1mpm1hcyv1ba1pkubtg1pmtv1zjm1nqtjr1lx1pixv1qdfm1bgor1ih1kwpwshx1gww1eml1mpm1hcyv1ba14j504f477s33347y795u70333473797w1qv1hrai1wwv’v1zlreclg1kft1iizvj1rwtb1itv1qtiizckcs1pqbj1flt

We think this is Vigenere Cipher (But, we do not have key)

3.	Decrypt Vigenere Cipher (https://www.guballa.de/vigenere-solver)
-	This tools decrypt vigenere w/o knowing the keys

![image](https://user-images.githubusercontent.com/44063862/49643230-1f0be100-fa50-11e8-8a10-66404e574aa9.png)

>well1the1flag1is1hidden1here1but1first1we1have1some1text1to1confuse1you1now1the1flag1is14b504d477b33347a795f70333473797d1in1fact1don’t1include1the1parts1that1are1separated1with1one

4b504d477b33347a795f70333473797d – Only take this part to be decrypt

4.	Cyber Chef (& Magic)

![image](https://user-images.githubusercontent.com/44063862/49643281-3a76ec00-fa50-11e8-955d-ecf101fd890c.png)

5.	Hex

![image](https://user-images.githubusercontent.com/44063862/49643298-4b276200-fa50-11e8-8044-f41ae098d967.png)

Flag: KPMG{34zy_p34sy}



