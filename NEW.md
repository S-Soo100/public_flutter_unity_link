# 플러터-유니티 위젯 설치
  나도 처음 해보는 작업이고 너무 어려우니까 하나씩 메모하면서 해보자
  
<ul>
   <li> 
     안드로이드 NDK 설치
  </li>
   <li> 
     안드로이드 스튜디오에서 해당 프로젝트를 연 후, NDK버젼 체크
  </li> 
  <li> 
     플러터 프로젝트에 /unity 폴더를 만들고, 그 안에 유니티 프로젝트 폴더 삽입
  </li> 
    <li> 
     유니티 에디터에서 build setting
        <ul>
          <li>
            빌드 세팅에서 scenes 추가
          </li>
          <li> 
             플랫폼을 안드로이드로 변경 
          </li> 
          <li> 
           Export Project 체크 후
            Compression Method는 [L74HC] 선택
          </li> 
          <li> 
             플랫폼 ios로 변경
          </li> 
          <li> 
           안드로이드와 동일하게 
            Compression Method는 [L74HC] 선택
          </li> 
          <li> 
            현재 세팅 창의 좌하단, Player Settings로 이동
          </li> 
          <li> 
            <p>
            Android → Other Settings → Configuration → Scripting Backend → IL2CPP 선택
            <p/>
            <p>
                Target Architectures → ARMv7과 ARM64 체크
            </p>
          </li>
          <li> 
            iOS → Other Settings → Configuration → Scripting Backend → IL2CPP 확인
          </li> 
          <li>
            Target SDK → Device SDK 선택
          </li>
        </ul>
  </li> 
</ul>

## NDK 다운로드
링크: https://developer.android.com/ndk/downloads?hl=ko
