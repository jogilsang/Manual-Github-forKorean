# Manual-Github

### 링크
- Github 사용법 및 올리는법 - 시행착오 많이겪음 및 에러 해결

https://blog.naver.com/jogilsang/221236806980

```
(readme)
 echo "# android-template-2" >> README.md

(new)
git config --global user.name "jogilsang"
git config --global user.email jogilsang@gmail.com
git init
git status
git add -A
git commit -m "update"
git remote add origin [git address]
git push -f origin master

(modifyed)
git add -A
git commit -m "update"
git push -f origin master

(특정경로,특정폴더)
git init copyGit
cd copyGit
git remote add -f origin <REMOTE_URL>
echo "MyTabLayout" >> .git/info/sparse-checkout
git pull origin master

echo "MyTabLayout/etc" >> .git/info/sparse-checkout

src : https://www.lesstif.com/pages/viewpage.action?pageId=20776761

(down)
git clone [git address]
git pull [git address]
```




- Github의 Fork한 Repository 삭제

https://blog.naver.com/jogilsang/221377073174

<hr/>

### tablayout tab scroll 텝스크롤 탭스크롤 
```
        tabLayout.setTabGravity(TabLayout.GRAVITY_FILL);
        tabLayout.setTabMode(TabLayout.MODE_SCROLLABLE);
       
```

### 타이틀바 상태바 액션바 titlebar actionbar bar
android:theme="@android:style/Theme.NoTitleBar"  


### 작성법
1. 라인피드(Linefeed)
- 줄에다가 스페이스+스페이스 를 넣는다
```
사람을 존경하라,  
그러면 그는 더 많은 일을 해 낼 것이다.
```
- 아무생각없이 엔터를 친다면, 
```
사람을 존경하라,

그러면 그는 더 많은 일을 해 낼 것이다.
```

2. 이미지 리사이즈(Image Resize)

- git 파일내부 
```
"![](/11.png)"

android : 375 x 667
```
![](/11.png)

- git 파일 리사이즈 1
```
<center><img src="/11.png" width="375" height="667"></center>
```
<center><img src="/11.png" width="375" height="667"></center>

- 웹 페이지 가져오기
```
![](https://blogpfthumb-phinf.pstatic.net/MjAxNzEyMDhfMTMy/MDAxNTEyNzA3MTc0ODA3.rbnlwP_k8OCxoan813kT-Q0DVAxw8Vgb0co6Ivpcg1Yg.QdHiNjmkf1OVkzCy8ZIyyy1cjDe2947sLVuj9vynVpQg.PNG.jogilsang/JS.png?type=w161)
```
![](https://blogpfthumb-phinf.pstatic.net/MjAxNzEyMDhfMTMy/MDAxNTEyNzA3MTc0ODA3.rbnlwP_k8OCxoan813kT-Q0DVAxw8Vgb0co6Ivpcg1Yg.QdHiNjmkf1OVkzCy8ZIyyy1cjDe2947sLVuj9vynVpQg.PNG.jogilsang/JS.png?type=w161)



