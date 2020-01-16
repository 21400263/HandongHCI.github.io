[← go back to the list](../README.md)

# Portable Micro-dust Device(PMD) Project - 휴대용 미세먼지 측정기

#### Members
- 김태운, 박성경, 유재은

## 1. 제품 설명 ###

본 제품은 기존에 존재하는 미세먼지 측정기기에서 더 나아가 사용자가 있는 정확한 장소에서의 미세먼지 수치를 측정할 수 있는 기기이다. 단순한 미세먼지 측정기능뿐만 아니라
 
1) GPS기능을 사용한 위치 알림 기능
2) 어플리케이션을 활용한 미세먼지 정보 공유
3) 넓은 수납 공간
등의 기능을 가지고 있다.


## 2. 부품설명
1. 라즈베리 파이

미세먼지 센서를 작동 시키고 센서로 부터 측정된 데이터를 어플리케이션과 연동시키는 기기이다. 

![raspberry](img/raspberry.jpg)

2. 미세먼지 센서

외부의 미세먼지 정도를 측정하여 데이터 값으로 변환하는 기기이다. 

![sensor](img/sensor.jpg)

3. 외관

라즈베리 파이와 미세먼지 센서를 내장하고 추가적인 수납 공간을 제공한다. 

[정면]

![judy](img/judy.jpg)

[후면]

![judy2](img/judy2.jpg)

[수납공간]

![judy3](img/judy3.jpg)


## 3. PMD사용방법
1. PMD과 보조 베터리를 가지고 원하는 장소로 이동한다.
2. 원하는 장소에 도착하여 보조 베터리를 사용하여 PMD의 전원을 연결시킨다.  
3. 핸드폰에서 'PMD' 어플리케이션을 사용하여 원하는 장소의 미세먼지를 측정한다. 
   - [어플리케이션 사용 체험 (app prototype)](https://www.figma.com/proto/Yrtwzbvl1vuXj5vnoqI8gPbF/%EC%95%84%EC%9C%B5%EC%9E%85?node-id=0%3A1&scaling=min-zoom)

## 4. PMD 어플리케이션 사용방법 ###
1. 회원가입: 어플리케이션 소개글을 읽고 회원가입 버튼을 누른다.
2. 아이디 중복을 확인하고 필요정보를 입력한 후 회원가입을 한다.
3. 로그인: 회원가입을 한 아이디와 비밀번호로 로그인을 한다. 
4. 기본화면: 가장 먼저 자신의 현재 위치가 측정되며 미세먼지 정도를 보여준다.
   <p>4-1. 상세정보: 미세먼지에 대한 자세한 정보를 보고 싶으면 '상세정보' 버튼을 누른다.
   <p>4-2. 위치변경: 현재 위치가 잘못 측정되었을 경우 '위치변경' 버튼을 눌러 수정한다. 
5. 위치 변경에서 이전에 측정하였던 장소를 택할 수 있다. 
   <p>5-1. 목록추가:목록에 없는 장소를 추가하고 싶으면 '목록추가' 버튼을 누른다. 
   <p>5-2. 추가: 목록추가 화면에서 주소를 찾아 입력하고 '추가' 버튼을 누른다.
6. 다른 회원의 정보가 필요할 경우 기본 화면 하단의 '추가' 버튼을 누른다. 
   <p>6-1. 회원 추가: 아이디를 사용하여 원하는 회원을 검색한다. 
   <p>6-2. 선택: 원하는 회원을 선택하고 '추가' 버튼을 누른다. 이때 상대방에게 초대 알림이 
              발송되고 상대방이 수락할 경우 회원목록에 반영된다. 
7. 다른 회원 정보: 다른 회원의 자세한 정보가 필요할 경우 그 회원 목록 하단의 '상세정보' 버튼을 누른다. 
8. 메뉴: 좌측 상단의 메뉴 모양의 버튼을 눌러 메뉴를 확인할 수 있다. 
   <p>8-1 프로필: 메뉴 화면에서 'My Profile'을 선택하여 사진 변경 밑 다른 정보를 수정할 수 있다.
   <p>8-2 로그아웃: 로그아웃이 필요할 경우 설정 화면에서 '로그아웃' 버튼을 눌러 로그아웃 할 수 있다. 
   <p>8-3 알림: 메뉴 화면 우측 상단에서 알림을 확인하고 종 모양의 버튼을 눌러 정보를 확인할 수 있다. 
9. 알림 확인: 다른 회원의 친구신청 목록을 확인할 수 있다. 
   <p>9-1 친구 추가: 다른 회원의 친구 신청을 허락할 경우 '추가' 버튼을 눌러 허락할 수 있다. 
   <p>9-2 친구 거절: 다른 회원의 친구 신청을 허락하지 않을 경우 '삭제' 버튼을 눌러 거절할 수 있다. 
10. 설정: 메뉴 화면이나 기본 화면에서 톱니바퀴 모양의 버튼을 눌러 어플리케이션의 설정을 변경할 수 있다. 
      <p> 10-1 위치공유: 설정 화면에서 위치공유 기능을 활성화/비활성화 할 수 있다. 


## 5. PMD 사용 주의사항
- 제품에 심한 충격이 가해질 경우 제품에 손상이 일어날 수 있습니다. 
- 과도한 제품의 사용은 제품의 과열을 일으킬 수 있습니다.
- 제품의 부분과 맞지 않는 보조 베터리를 사용할 경우 화재의 위험이 있습니다. 
- 제품의 내부 기기에 물이 닿지 않도록 주의하세요.



<br><br><br>
[← go back to the list](https://HandongHCI.github.io/StudentProjects/ICTprototyping2019S)