# KCSC_challenges
# Nguyễn Xuân Quốc - AT18N0142

# ****Tet_is_ya_best****

Đề bài cho ta 1 file chứa nội dung như sau

```
lyl, rwns dmsfm rn wkmrx myf iyrx pynljorw, jn luy ejvvynl lxrqjljsmrw pynljorw jm ojyl mrh.
lyl jn knkrwwi pxsh luy ymq sp trmkrxi ls yrxwi pyexkrxi. 
eypsxy lyl, ojylmrhyny cxycrxy hrmi lujmvn psx luy luxyy hrjm qrin. 
luyi gwyrm luyjx uskny rmq qygsxrly fjlu pwsfyxn nkgu rn dkhbkrl lxyy sx cyrgu ewsnnsh. 
r ukvy rhskml sp pssq fjww ey eskvul eypsxy lyl psx hrdjmv lxrqjljsmrw qjnuyn. ermu gukmv, ermu lyl, vjs gur, asj rmq hkl, …rmq grmqjyn rxy luy pssqn lurl hknl uroy sm lyl uswjqrin.
qkxjmv lyl, cyscwy ojnjl luyjx xywrljoyn’ ushyn rmq vjoy fjnuyn. 
usfyoyx, luy ojylmrhyny eywjyoy lurl luy pjxnl ojnjlsx r prhjwi xygyjoyn jm luy iyrx qylyxhjmyn luyjx psxlkmy psx luy ymljxy iyrx, cyscwy myoyx ymlyx rmi uskny sm luy pjxnl qri fjluskl eyjmv jmojlyq pjxnl. 
rmsluyx gknlsh jn vjojmv wkgdi hsmyi, fujgu jn ckl jmls r xyq ymoywscy rn r nihesw sp wkgd rmq fjnu psx r myf rvy. 
lxrqjljsmrwwi, ywqyxn fjww vjoy wkgdi hsmyi ls gujwqxym rmq luy swqynl cyscwy jm luy prhjwi. usfyoyx, msfrqrin, cyscwy grm vjoy jl ls rmismy jmgwkqjmv pxjymqn, crxymln, myjvuesxn,… 
eynjqyn, ojylmrhyny knkrwwi vs ls crvsqrn sx lyhcwyn ls cxri psx uyrwlu, fyrwlu, nkggynn,… 
ls ojylmrhyny, lyl jn luy urccjynl ljhy sp rww iyrx rxskmq, hyheyxn jm r prhjwi grm vrluyx lsvyluyx, fujgu jn r hyrmjmvpkw hynnrvyn sp wkmrx myf iyrx pynljorw. 
rww jm rww, lyl jn rww reskl ergd ls sxjvjmn, ey vssq ls sluyxn, ymtsi luy cxygjskn hshyml, rmq fjnu psx luy eynl ls gshy.
luy pwrv jn: dgng{lyl_lyl_lyl_lyl_qym_xsj__gukg_grg_erm_mrh_hsj_lurl_mujyk_nkg_dusy__wko_pxsh_wkwkkkkkkkkkkkk}
```

Nhìn vào nội dung của file mình nghĩ ngay đến Monoalphabetic Substitution Cipher

Dùng [https://www.guballa.de/substitution-solver](https://www.guballa.de/substitution-solver) để giải mã ta nhận được bản rõ là:

```
tet, also known as lunar new year festival, is the biggest traditional festival in viet nam.
tet is usually from the end of january to early february.
before tet, vietnamese prepare many things for the three main days.
they clean their house and decorate with flowers such as kumquat tree or peach blossom.
a huge amount of food will be bought before tet for making traditional dishes. banh chung, banh tet, gio cha, zoi and mut, …and candies are the foods that must have on tet holidays.
during tet, people visit their relatives’ homes and give wishes.
however, the vietnamese believe that the first visitor a family receives in the year determines their fortune for the entire year, people never enter any house on the first day without being invited first.
another custom is giving lucky money, which is put into a red envelope as a symbol of luck and wish for a new age.
traditionally, elders will give lucky money to children and the oldest people in the family. however, nowadays, people can give it to anyone including friends, parents, neighbors,…
besides, vietnamese usually go to pagodas or temples to pray for health, wealth, success,…
to vietnamese, tet is the happiest time of all year around, members in a family can gather together, which is a meaningful messages of lunar new year festival.
all in all, tet is all about back to origins, be good to others, enjoy the precious moment, and wish for the best to come.
the flag is: kcsc{tet_tet_tet_tet_den_roi__chuc_cac_ban_nam_moi_that_nhieu_suc_khoe__luv_from_luluuuuuuuuuuuu}
```

Vậy flag là :

KCSC{tet_tet_tet_tet_den_roi__chuc_cac_ban_nam_moi_that_nhieu_suc_khoe__luv_from_luluuuuuuuuuuuu}

# ****Chuyến tàu vô tận****

Ta nhân được file có nội dung như sau:

```
01010011 00110001 01000010 01010100 01010110 01101011 00110101 01010110 01010011 01101011 01001010 01010011 01010101 00110000 01000110 01001111 01010001 00110000 01001110 01001101 01010001 01010101 01010110 01000010 01010010 01010101 01010110 01001000 01010011 00110000 01110100 01010000 01010110 01010101 00111001 01000110 01010100 00110000 01010110 01000010 01010110 01000110 01010010 01010101 01010100 00110001 01001110 01000110 01010101 00110001 01001010 01010000 01010111 01010110 01001010 01000111 01010100 01000110 01001110 01001010
```

Mình có thể nhận biết được ngay đó là các chuỗi nhị phân 8bỉt nối tiếp nhau 

Sau đó, mình thử convert sang dạng mã ascii thì nhận được một chuỗi có dạng (dùng [https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8)](https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8))) 

```python
S1BTVk5VSkJSU0FOQ0NMQUVBRUVHS0tPVU9FT0VBVFRUT1NFU1JPWVJGTFNJ
```

Đoán được chuỗi là base64 nên mình convert thêm 1 lần nữa thì được 1 chuỗi mới (dùng [https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false))) :

```python
KPSVNUJBRSANCCLAEAEEGKKOUOEOEATTTOSESROYRFLSI
```

Đề bài tên là chuyến tàu vô tận nên mình nghĩ mật mã sẽ có gì đó liên quan đến tàu và mình tìm ra rail fence cipher (Mật mã hàng rào đường sắt)

Dùng [https://gchq.github.io/CyberChef/#recipe=Rail_Fence_Cipher_Decode(3,0)&input=S1BTVk5VSkJSU0FOQ0NMQUVBRUVHS0tPVU9FT0VBVFRUT1NFU1JPWVJGTFNJ](https://gchq.github.io/CyberChef/#recipe=Rail_Fence_Cipher_Decode(3,0)&input=S1BTVk5VSkJSU0FOQ0NMQUVBRUVHS0tPVU9FT0VBVFRUT1NFU1JPWVJGTFNJ)

Và tăng từ từ key lên để kiểm tra thì tại vị trí key = 3 nhận được:

```python
KCSCPLEASESAVERENGOKUKYOJUROBEFORELASTSTATION
```

Vậy Flag là:

KCSC{PLEASESAVERENGOKUKYOJUROBEFORELASTSTATION}

# ****ezenc****

Nội dung đề bài 

```python
4e544d7a4d44526c4e5451314d544d7a4e7a51304e6a59794e6d51305a5463324e5745304e7a5a6a4e7a553159544d784d7a6b305954597a4d7a457a4f5451304e6a497a4d6a4d354e7a4d304f54557a4e4455324f4459324e54457a5a444e6b304f54557a4e4455324f4459324e54457a5a444e6b
```

Đầu tiên có thể thấy bản mã đang ở dạng mã hex nên ta tiến hành giải mã → thu được:

```python
NTMzMDRlNTQ1MTMzNzQ0NjYyNmQ0ZTc2NWE0NzZjNzU1YTMxMzk0YTYzMzEzOTQ0NjIzMjM5NzM0OTUzNDU2ODY2NTEzZDNk0OTUzNDU2ODY2NTEzZDNk
```

Đoán được bản mã mới là base64 nên tiếp tục giải mã → thu được:

```python
53304e5451337446626d4e765a476c755a31394a63313944623239734953456866513d3d͐
```

bản mã lại ở dạng mã hex nên lặp lại 2 bước trên 1 lần nữa ra thu được flag là:

KCSC{Encoding_Is_Cool!!!}

# ****Waiting xor you****

Theo đề bài thì ta có thể đoán được challenge này có liên qua đến phép xor

Ta nhận được source code 

```python
def xor(a: bytes, b: bytes):
    return bytes([a[i % len(a)] ^ b[i % len(b)] for i in range(max(len(a), len(b)))])

flag = b"KCSC{???????????????????????????}"
key = b"??????"
print(xor(flag, key))
#b'>0\x0c,\x1a+:=\x100(5*,\x08*(2<=\x11!> E!\x006Q3VP"'
```

Đoán được flag sau khi được xor với key sẽ có dạng:

```python
b'>0\x0c,\x1a+:=\x100(5*,\x08*(2<=\x11!> E!\x006Q3VP"'
```

Ta có thể đoán được 1 phần của key bằng cách xor đoạn mã trên với “KCSC{” thu được:

```python
b'us_oa`ynSKcvyosaka\x7fFZbmc>jCe\x12H\x1d\x13q'
```

Đoán được ngay key là “us_oaf”

⇒ Flag:

```python
KCSC{MONO_IS__WEITINNN_F0R_Y0U##}
```
