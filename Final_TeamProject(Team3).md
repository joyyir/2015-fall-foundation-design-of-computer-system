<div style="text-align:center">
<font size="20">컴퓨터시스템 기초설계 </font>
</div>

Team 2
2011136006 고현영
2011136025 김재휘
2011136102 장준영

<font style="bold" size=7>목차</font>

[TOC]

##1. 문제 정의 및  요구사항 정의
###1.1 문제상황
> 초등학교 1학년 딸을 둔 김경로(37), 김경순(34) 부부. 맞벌이 부부이고 둘 다 출근시간이
촉박하다보니 거의 매일 아이 스스로 등교를 시키는 편이다.
아이는 방과후에 학원버스를 타고 피아노학원을 다니고, 피아노 학원이 끝난 뒤에는
동네 놀이터에서 친구들과 놀기도 하고 친구 집에 놀러 가기도 한다. 회사에 있는 부부는
딸이 방과후에 학원은 잘 갔는지, 위험한 장소에 가서 놀지는 않는지 항상 걱정한다.
뉴스에서는 어린이 유괴 사건이 끊이질 않고, 학교 주변에 유해업소가 계속해서 생겨나서
아이들 정신에 해롭다는 보도가 이어진다.

---

###1.2 문제정의(5Whys)

|순 서|질 문|답 안|
|:---:|:---|:---|
|1|왜 아이들은 유괴의 위험이 있거나 유해한 업소가 즐비한 길에 다니게 되는가? | 아이들은 어느 길이 위험하고 유해한 길인지 판단하는 기준이 없고 무지하기 때문이다
|2|왜 아이들은 어느 길이 위험하고 유해한지에 대해 무지할까? | 삶의 경험이 부족하고 그런 길을 다니게 됐을 때 즉시 옆에서 알려주는 사람이 없기 때문이다.|
|3|삶의 경험이 부족하고 그런 길을 다니게 됐을 때 즉시 옆에서 알려주는 사람이 없기 때문이다. | 보호자들도 각자의 일이 있기 때문에 항상 아이의 옆에서 돌볼 수 없기 때문이다.
|4|항상 부모가 옆에 있는 것처럼 아이들이 안전한 경로로 다니도록 도울 수 있는 방법은 없는가? | 아이가 항상 소지하고 다니는 기기를 이용한다.
|5|아이가 항상 소지하고 다니는 기기를 어떻게 활용하면 될까?|안전한 경로를 벗어났을 때 아이에게 알림을 주도록 하고, 부모에게 아이의 위치를 전송한다.

###1.3 진짜 문제 정의
> 아이들이 유괴 같은 범죄의 위험이나 유해업소의 노출이 없는 안전한 길로 다닐 수 있도록 해야 한다.


###1.4 필요성

> ![1-4.png](https://github.com/joyyir/comsisul/blob/master/img/1-4.png?raw=true)
> 2013년 경찰통계 연보에 따르면, 매년 실종아동의 수가 증가하고 있다. 또한 2014년 검찰청 통계 자료에 의하면, 아동유괴범죄의 발생장소 중 ‘노상’이 41.7%로 제일 빈번이 발생함을 확인할 수 있다. 아동유괴 범죄의 가해자는 지인, 친족, 이웃 등 아는 사람에 의해 발생한 경우가 대다수였다. 아동유괴범죄는 아동성폭력범죄까지 더하여 점점 그 질이 나빠져 가고 있다.
  이 통계를 바탕으로 우리는 아동유괴범죄를 사전에 예방하는 방법에 초점을 두었다. 왜냐하면 범죄가 발생한 후에 범인을 잡고 심판하는 것도 중요하지만, 사전에 범죄가 일어나지 않도록 하는 예방이 더 중요하고 생각했기 때문이다. 그래서 범죄를 예방하기 위한 수단으로 최근에 많이 확산된 스마트 기기를 이용해보기로 하였다. 최근에는 부모님들이 아이에게 스마트 기기를 소지하게 하지만, 아이들에게는 장난감에 불과할 뿐 이를 활용하여 비상상황에 대비할 수 있는 기능을 사용하는 아이는 거의 없다. 이런 스마트 기기를 이용하여 실시간으로 현재 아동의 위치와 상황을 보호자에게 알려줄 수 있는 시스템이 요구된다.

###1.5 요구 사항
 -> 아이가 안전한 길을 벗어났을 때 아이에게 경고 알람이 울린다.
 -> 보호자는 아이의 위치를 실시간으로 파악할 수 있다.
 -> 아이나 보호자는 디바이스를 통해 위험한 길 혹은 안전한 길이 어디 있는지 확인할 수 있다.
 -> 가볍고 견고한 웨어러블 디바이스를 사용한다.
 -> 아이들의 정서 및 취향에 맞는 디바이스 디자인을 사용한다.

##2. 유사 서비스 및 차별점
###2.1 유사 서비스 소개 : 헬프맘
![2-1.png](https://github.com/joyyir/comsisul/blob/master/img/2-1.png?raw=true)
> 주요 기능
1. 경로이탈 알림 서비스 : 보호자(부모)가 보호대상자(자녀)의 이동경로를 전자지도에 입력한 후 보호대상자(자녀)가 설정 경로, 경계(ex:30m)를 이탈하면 보호자와 보호대상자에게 문자전송으로 이탈을 알려 유인 또는 유괴에 의한 성범죄, 학교폭력 및 금품갈취를 예방하는 오직 “헬프맘”만의 특별한 서비스 입니다 .
2. 위치확인 맵 서비스 : 보호자가 핸드폰으로 실시간 보호대상자(자녀)의 위치를 확인할 수 있는 서비스입니다. 
3. 안전지대 설정 서비스 : 안전지대(ex:집, 학교, 학원)를 지정하여 이탈시 보호자(부모)와 보호대상자(자녀)에게 문자전송으로 이탈을 알려주는 서비스입니다.
4. 전원차단 알림 서비스 : 보호대상자(자녀)가 핸드폰 전원 차단시 보호자(부모)에게 문자전송을 통하여 알려주는 서비스입니다.
5. GPS차단 알림 서비스 : 보호대상자(자녀)가 설정경로에 있더라도 자,타의에 보호대상자(자녀) 핸드폰 GPS수신 불가시 보호자(부모)에게 문자 전송하여 실내로 유인 또는 유괴에 의한 성범죄, 학교폭력 및 금품갈취를 예방하는 서비스입니다. 
6. 이동정지 알림 서비스 : 보호대상자(자녀)가 설정경로 이동 중 일정시간(ex:3분) 정지 시 보호자(부모)에게 문자전송으로 유인 또는 유괴에 의한 성범죄, 학교폭력 및 금품갈취를 예방하는 서비스입니다. 

##2.2 유사 서비스와의 차별점
![2-3.png](https://github.com/joyyir/comsisul/blob/master/img/2-1.png?raw=true)



##3. 시스템 설계

###3.1 시스템의 목적
아이들이 유괴 같은 범죄의 위험이나 유해업소의 노출이 없는 안전한 길로 다닐 수 있도록 하는 시스템을 구현한다.

###3.2 시스템의 기능
![3-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-2.png?raw=true)

###3.3 시스템 구조
####3.3.1 전체 시스템 구성도
![3-3-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-1.png?raw=true)

####3.3.2  자녀용 S/W
![3-3-2-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-2-1.png?raw=true)
![3-3-2-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-2-2.png?raw=true)
![3-3-2-3.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-2-3.png?raw=true)

####3.3.3 서버용 S/W
![3-3-3-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-3-1.png?raw=true)
![3-3-3-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-3-2.png?raw=true)

####3.3.4 보호자용 S/W
![3-3-4-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-4-1.png?raw=true)
![3-3-4-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-4-2.png?raw=true)
![3-3-4-3.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-4-3.png?raw=true)

####3.3.5 데이터베이스 구조
![3-3-5.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-5.png?raw=true)


####3.3.6 데이터 흐름도
![3-3-6-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-6-1.png?raw=true)
![3-3-6-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-6-2.png?raw=true)
![3-3-6-3.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-6-3.png?raw=true)
![3-3-6-4.png](https://github.com/joyyir/comsisul/blob/master/img/3-3-6-4.png?raw=true)

###3.4 기능별 시스템 요소간 동작흐름
![3-4-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-1.png?raw=true)
![3-4-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-2.png?raw=true)
![3-4-3.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-3.png?raw=true)
![3-4-4.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-4.png?raw=true)
![3-4-5.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-5.png?raw=true)
![3-4-6.png](https://github.com/joyyir/comsisul/blob/master/img/3-4-6.png?raw=true)

###3.5 시스템 프로토타입
####3.5.1 자녀용 S/W
![3-5-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-5-1.png?raw=true)

####3.5.2 보호자용 S/W
![3-5-2-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-5-2-1.png?raw=true)
![3-5-2-2.png](https://github.com/joyyir/comsisul/blob/master/img/3-5-2-2.png?raw=true)

###3.6 상세 설계
####3.6.1 자녀용 App 주요 모듈 구조
>![3-6-1.png](https://github.com/joyyir/comsisul/blob/master/img/3-6-1.png?raw=true)
> **1.4 정보 전송 모듈**
> |DataSendModule|정보 전송 모듈. 외부로 데이터를 보내는 기능 수행|
> |:--|:--|
>| -m_singleton : DataSendModule <br/> - m_serverSock : Socket<br/>-m_oos : ObjectOutputStream<br/>-m_data : Data|싱글톤 객체<br/>외부 접속자의 소켓 정보<br/>객체 직렬화를 통해 외부 접속자 소켓으로 데이터를 보냄<br/>전송할 데이터
>| +getInstance() : DataSendModule<br/>+openServerSock() : void<br/>+makeDataObject(char, Subdata) : void<br/>+sendData() : void<br/>+close() : void|싱글톤 객체를 반환한다.<br/>외부 접속자의 소켓을 연다.<br/>전송할 데이터를 준비한다.<br/>데이터를 외부로 전송 <br/>외부 접속자의 소켓을 닫는다.
>
>**Pseudocode**
>**1) getInstance() : DataSendModule**
>```
>public DataSendModule getInstance(){
   return m_singleton;
}
>```
>**2) openServerSock() : void**
>```
>public void openServerSock(){
>   InetAddress serverIP = null;
>   int portNum = 0;
>   
>   try {
>      m_serverSock = new Socket(serverIP, portNum);
>   } catch (IOException e) {
>      e.printStackTrace();
>   }
>}
>```
>
>**3) makeDataObject(char command, SubData sdata) : void**
>```
>public void makeDataObject(char command, SubData sdata){
>   m_data.setCommand(command);
>   m_data.setSenderID(Common.getUserID());
>   m_data.setReceiverID(Common.getParentID());
>   m_data.setCurrentTime(Common.getCurTime());
>   
>   switch(command){
>      case 
>Data.COMMAND_CHILD_RESPONSE_LOCATION_TO_PARENT :      
>m_data.setLongtitude(Common.getLongtitude());
>         m_data.setLatitude(Common.getLatitude());
>         break;
>      case XXX :
>      m_data.setxxx(yyy);
>         ...
>         break;
>      case ...
>      ...
>   }   
>}
>```
>**4) sendData() : void**
>```
>public void sendData(){
>   try {
>      m_oos = new 
>ObjectOutputStream(m_serverSock.getOutputStream());
>      m_oos.writeObject(m_data);
>      m_oos.flush();
>      m_serverSock.close();
>   } catch (IOException e) {
>      e.printStackTrace();
>   }
>}
>```
>**5) close() : void**
>```
>public void close(){
>   try {
>      m_serverSock.close();
>      m_oos.close();
>   } catch (IOException e) {
>      e.printStackTrace();
>   }
>   m_data = null;
>}
>```
>**1.5 정보 수신 모듈**
>|DataReceiveModule|정보 수신 모듈. 외부로부터 데이터를 받아들이는 기능 수행|
> |:--|:--|
>|-m_singleton : DataReceiveModule<br/>-m_receiveSock : ServerSocket<br/>-m_sock : Socket-m_ois : ObjectInputStream<br/>-m_data : Data|싱글톤 객체<br/>데이터를 받아들이는 소켓<br/>외부 접속자의 소켓 정보<br/>객체 역직렬화를 통해 외부 접속자 소켓으로부터 데이터를 읽음<br/>수신한 데이터
>|+getInstance() : DataReceiveModule<br/>+openReceiverSock() : void<br/>+receiveData() : void<br/>+processDataObject() : void<br/>+close() : void|싱글톤 객체를 반환한다.<br/>데이터를 받아들이는 소켓을 연다.<br/>데이터를 외부로부터 수신<br/>수신한 데이터를 명령에 따라 처리<br/>데이터를 받아들이는 소켓을 닫는다.
>
>**Pseudocode**
>**1) getInstance() : DataSendModule**
>```
>public DataSendModule getInstance(){
>   return m_singleton;
>```
>**2) openReceiverSock() : void**
>```
>public void openReceiveSock(int portNum){
>   try {
>      m_receiveSock = new ServerSocket(portNum);
>   } catch (IOException e) {
>      e.printStackTrace();
>   }
>}
>```
>**3) receiveData() : void**
>```
>public void receiveData(){
>   while(true){
>      try {
>         m_sock = m_receiveSock.accept();
>         m_ois = new ObjectInputStream(m_sock.getInputStream());
>         m_data = (Data)m_ois.readObject();
>         processDataObject();
>         sock.close();
>      } catch (Exception e) {
>         e.printStackTrace();
>      }
>   }
>}
>```
>**4) processDataObject() : void**
>```
>public void processDataObject(){
>switch(m_data.getCommand()){
>      case Data.COMMAND_SERVER_SEND_DANGERINFO_TO_CHILD :
>         AlarmModule.getInstance().ringAlarm(m_data.isDanger());
>         break;
>      case Data.COMMAND_PARENT_REQUEST_FOR_LOCATION_TO_CHILD :
>         DataResponseModule.getInstance().responseToRequestLocation();
>         break;
>      case xxx : yyy
>      ...
>   }
>}
>```
>**5) close() : void**
>```
>public void close(){
>   try {
>      m_receiveSock.close();
>      m_sock.close();
>      m_ois.close();
>   } catch (IOException e) {
>      e.printStackTrace();
>   }
>   m_data = null;
>}
>```
>**1.7 정보 요청 모듈**
> |DataResponseModule|정보 요청 응답 모듈. 요청된 데이터를 요청자에게 전송한다.|
> |:--|:--|
>|-m_singleton : DataResponseModule|싱글톤 객체|
>|+getInstance() : DataReceiveModule<br/>+responseToRequestLocation() : void<br/>+responseToRequestOnOffInfo() : void|싱글톤 객체를 반환한다.<br/>위치 정보 요청에 대해 응답한다.<br/>전원차단여부, GPS차단여부 정보 요청에 대해 응답한다.
>
>**Pseudocode**
>**1) getInstance() : DataSendModule**
>```
>public DataSendModule getInstance(){
>   return m_singleton;
>}
>```
>**2) responseToRequestLocation() : void**
>```
>public void responseToRequestLocation(){
>   String senderID = Common.getInstance().getUserID();
>   String receiverID = Common.getInstance().getParentID();
>      int longitude = Common.getInstance().getLongitude();
>   int latitude = Common.getInstance().getLatitude();
>
>DataSendModule.getInstance().makeDataObject(Data.COMMAND_CHILD_RESPONSE_LOCATION_
>      TO_PARENT, senderID, receiverID, longtitude, latitude);
>   DataSendModule.getInstance().sendData();
>   DataSendMoudle.close();
>}
>```
>**3) responseToRequestOnOffInfo() : void**
>```
>public void responseToRequestOnOffInfo(){
>   String senderID = Common.getInstance().getUserID();
>   String receiverID = Common.getInstance().getParentID();
>   boolean gpsOnOffInfo = Common.getInstance().getGpsOnOffInfo();
>   DataSendModule.getInstance().makeDataObject(Data.COMMAND_CHILD_RESPONSE_ONOFFINFO_
>      TO_SERVER, senderID, receiverID, gpsOnOffInfo);
>   DataSendModule.getInstance().sendData();
>   DataSendMoudle.close();
>}
>```
>
>**Data 클래스 구조**
>|Data|서버와 클라이언트(자녀용 기기, 보호자용 기기) 사이에 통신으로 전달되는 객체|
> |:--|:--|
> |-m_command : char<br/>-m_sender_ID : String<br/>-m_receiverID : String<br/>-m_longitude : double<br/>-m_latitude : double<br/>-m_currentTime : long<br/>-m_isDanger : boolean<br/>-m_dangerCode : int<br/>-m_isPowerOn : boolean<br/>-m_isGpsOn : boolean<br/>-m_startLongitude : double<br/>-m_startLatitude : double<br/>-m_endLongitude : double<br/>-m_endLatitude : double<br/>-m_safePath : SafePath|수신 단에서 처리해야할 명령을 명시<br/>송신자의 계정 ID<br/>송신자의 계정 ID<br/>위도<br/>경도<br/>현재 시간<br/>위험 여부<br/>(위험할 경우) 위험 유형<br/>전원 차단 여부<br/>GPS 차단 여부<br/>출발지 위도<br/>출발지 경도<br/>도착지 위도<br/>도착지 경도<br/>안전경로 정보
> |// getter<br/>+getCommand() : char<br/>+getSenderID() : String<br/>...(생략)...<br/>+getEndLatitude() : double<br/><br/>// setter<br/>+setCommand(char command) : void<br/>+setSenderID(String senderID) : void<br/>...(생략)...<br/>+setEndLatitude(int endLatitude) : void|// getter<br/>멤버 변수 m_command의 값을 반환<br/>멤버 변수 m_senderID의 값을 반환<br/>...(생략)...<br/>멤버 변수 m_endLatitude의 값을 반환<br/><br/>// setter<br/>멤버 변수 m_command의 값을 수정<br/>멤버 변수 m_senderID의 값을 수정<br/>...(생략)...<br/>멤버 변수 m_endLatitude의 값을 수정
>**Pseudocode 생략**
>

####3.6.2 서버용 App 주요 모듈 구조
>![3-6-2png](https://github.com/joyyir/comsisul/blob/master/img/3-6-2.png?raw=true)
>**2.3 안전 판단모듈**
>|JudgeSafetyModule|안전한 경로인지 판단하는 기능을 수행|
>|---|---|
>|-m_isDanger : boolean<br>-m_childx : int<br>-m_childy : int<br>-m_dangerx[] : int<br>-m_dangery[] : int<br>-m_searchRange : int<br>-m_serviceKey : long<br>-apiInfo : JSONObject <br>-url : URL<br>|위험 여부<br>자녀의 x좌표<br>자녀의 y좌표<br>위험지역 x좌표 배열<br>위험지역 y좌표 배열<br>API 탐색 범위<br>API의 서비스키 값<br>API에서 Json으로 파싱<br>API의 주소|
>|+getAPI() : int<br>+getPosition() : int<br>+comparePosition() : boolean|멤버 변수 m_dangerx, m_dangery 반환<br>멤버 변수 m_childx, m_childy 반환<br>자녀의 위치와 위험지역을 비교|
><br>
>**Pseudocode**
>```
>boolean JudgeSafetyModule(int m_childx,int m_childy)
>{
>   String m_serviceKey="a#@afdsa@#$$!3CBHA#$SDFr4525dDFG";
>   boolean m_isDanger=false;
>   int[] m_dangerx;
>   int[] m_dangery;
>   JSONObject apiInfo;
>
>   // openAPI에서 가져오기
>   URL url = new URL("http://www.theDanger.kr?ServiceKey=" + m_serviceKey + "&range=" + m_searchRange);
>   InputStreamReader isr = new InputStreamReader(url.openConnection().getInputStream(), "UTF-8");
>   JSONObject apiInfo = (JSONObject)JSONValue.parseWithException(isr);
>   JSONObject channel = (JSONObject)(apiInfo.get("channel"));
>
>
>   JSONArray x = (JSONArray)channel.get("x");
>   JSONArray y = (JSONArray)channel.get("y");
>
>
>   for(int i = 0 ; i < x.size(); i++) {
>   m_dangerx[i] = x.get(i).parseInt();
>   m_dangery[i] = y.get(i).parseInt();         
>   }
>
>  // 위험한 위치들과 비교해보고 겹치면 위험한 곳
>   for(int i=0; i<x.size;i++){
>
>      if((m_dangerx[i]-10<m_childx&&m_dangerx[i]+10>m_childx)&&(m_dangery[i]-10<m_childy&&m_dangery[i]+10>m_childy)){
>         m_isDanger=true;
>         break;
>      }
>   }
>
>   return m_isDanger;
>}
>```

>**2.4 안전 경로 도출 모듈**
>|DeductRouteModule|안전한 경로를 찾아내는 기능을 수행|
>|---|---|
>|-m_startLongitude : double<br/>-m_startLatitude : double<br/>-m_endLongitude : double<br>-m_endLatitude : double<br/>m_dangerx[] : int<br/>m_dangery[] : int<br/>m_searchRange : int<br/>m_serviceKey : long<br/>apiInfo : JSONObject <br/>url : URL|출발지 위도<br/>출발지 경도<br/>도착지 위도<br/>도착지 경도<br/>위험지역 x좌표 배열<br/>위험지역 y좌표 배열<br/>API 탐색 범위<br/>API의 서비스키 값<br/>API에서 Json으로 파싱<br/>API의 주소|
|+getAPI() : int<br/>+findSafeRoute() : int<br/>+getStEnPosition() : int<br/>|멤버 변수 m_dangerx, m_dangery 반환<br/>안전한 경로를 찾는 함수<br/>출발지 위도, 경도, 도착지 위도, 경도 반환|
>**Pseudocode**
>```>
>double[][] DeductRouteModule(double m_startLongitude, <br/>
>   double m_startLatitude, double m_endLongitude, double m_endLatitude)
>{
>   double[][] m_route;
>   String m_serviceKey="a#@afdsa@#$$!3CBHA#$SDFr4525dDFG";
>   int[] m_dangerx;
>   int[] m_dangery;
>   
>   JSONObject apiInfo;

>   // openAPI에서 가져오기
>   URL url = new URL("http://www.theDanger.kr?ServiceKey=" + m_serviceKey + "&range=" + m_searchRange);
>   InputStreamReader isr = new InputStreamReader(url.openConnection().getInputStream(), "UTF-8");
>   JSONObject apiInfo = (JSONObject)JSONValue.parseWithException(isr);
>   JSONObject channel = (JSONObject)(apiInfo.get("channel"));
>
>   JSONArray x = (JSONArray)channel.get("x");
>   JSONArray y = (JSONArray)channel.get("y");
>
>   for(int i = 0 ; i < x.size(); i++) {
>      m_dangerx[i] = x.get(i).parseInt();
>      m_dangery[i] = y.get(i).parseInt();         
>   }
>
>   //Astar 알고리즘을 이용해 위험지를 피해 가장 빠르게 목적지까지
>   //도달할 수 있도록 알고리즘 작성
>   m_route = findRouteByAstar(double m_startLongitude, 
>   double m_startLatitude, double m_endLongitude, double m_endLatitude);
>
>   return m_route;
>}
>```

>**2.5 정보 처리 모듈**
>|DataProcessModule|정보 처리 모듈. 수신된 데이터를 각 상황에 맞는 데이터로 변환|
>|---|---|
>|-m_query : String<br/>-m_database : String<br/>-m_database_address : String|데이터베이스와 주고 받을 SQL 쿼리문<br/>데이터베이스<br/>데이터베이스 주소|
>|+setquery<br/>+setdatabase<br/>+setdatase_address<br>+getquery<br>+getdatabase_address<br>+getdatabase_address<br><br>+addMember(String user) : void<br>+dltMember(String user) : void<br>+modMember(String user) : void<br>+isMember(String user) : boolean<br><br>+writeSafePath(Data data) : void<br>+readSafePath(Data data) : Data<br>+isSafePath(Data data) : boolean<br><br>+getResultData(char cmd) : Data|멤버 변수 m_query의 값을 수정<br>멤버 변수 m_database의 값을 수정<br>멤버 변수 m_database_address의 값을 수정<br>멤버 변수 m_query의 값을 반환<br>멤버 변수 m_database의 값을 반환<br>멤버 변수 m_database_address의 값을 반환<br><br>회원가입에 따른 DB 수정<br>회원탈퇴에 따른 DB 수정<br>회원수정에 따른 DB 수정<br>이용자DB에 user 계정 일치 여부 확인<br><br>부모로부터 설정된 안전경로를 DB로 전송<br>부모로부터 설정된 안전경로를 DB로부터 받아옴<br>안전경로DB와 인자로 들어간 path를 비교하여 안전경로 확인<br><br>Data에 저장된 m_command에 따라 처리 및 결과 반환|
><br>
>**Pseudocode**
>```
>import java.sql.PreparedStatement;
>import java.sql.SQLException;
>
>/**
> * Created by Hyunyoung98 on 2015-11-20.
> */
>public class tmp {
>    private String m_query;
>    private String m_database;
>    private String m_table;
>    private String m_database_address;
>
>    //멤버 변수 m_query의 값을 수정
>    public void setquery(String query){
>        m_query = query;
>    }
>
>    //멤버 변수 m_database의 값을 수정
>    public void setdatabase(String database){
>        m_database = database;
>    }
>
>    //멤버 변수 m_database_address의 값을 수정
>    public void setdatabase_address(String database_address){
>        m_datavase_address = database_address;
>    }
>
>    //멤버 변수 m_table의 값을 수정
>    public void settable(String table){
>        m_table = table;
>    }
>
>    //멤버 변수 m_query의 값을 반환
>    public String getquery(){
>        return m_query;
>    }
>
>    //멤버 변수 m_database의 값을 반환
>    public String getdatabase(){
>        return m_database;
>    }
>
>    //멤버 변수 m_database_address의 값을 반환
>    public String getdatabase_address(){
>        return m_datavase_address;
>    }
>
>    //멤버 변수 m_table의 값을 반환
>    public String gettable(){
>        return m_table;
>    }
>
>    //회원가입에 따른 DB 수정
>    public void addMemeber(User userInfo){
>        //java.sql 모듈 이용
>        PreparedStatement pstmt = null;
>        String sql = null;
>
>        try {
>            //insert 쿼리문 작성
>            sql="insert into (userID,userPW,userName,userCode,userAddress) values (?,?,?,?,?)";
>            pstmt.setString(1,userInfo.getID());
>            pstmt.setString(2,userInfo.getPW());
>            pstmt.setString(3,userInfo.getname());
>            pstmt.setString(4,userInfo.getcode());
>            pstmt.setString(5,userInfo.getaddress());
>
>            pstmt.execute();
>        } catch (SQLException e) {
>            e.printStackTrace();
>        }
>    }
>
>    //회원탈퇴에 따른 DB 수정
>    public void dltMemeber(User userInfo){
>        //java.sql 모듈 이용
>        PreparedStatement pstmt = null;
>        String sql = null;
>        try {
>            //delete 쿼리문 작성
>            sql="delete from "+m_table+" where userID = ?";
>            pstmt.setString(1,userInfo.getID());
>
>            pstmt.execute();
>        } catch (SQLException e) {
>            e.printStackTrace();
>        }
>    }
>
>    //회원수정에 따른 DB 수정
>    public void modMemeber(User userInfo){
>        //java.sql 모듈 이용
>        PreparedStatement pstmt = null;
>        String sql = null;
>        try {
>            //update 쿼리문 작성
>            sql="update "+m_table+" set userPW = ?, userName = ?, userCode = ?, userAddress = ?";
>            //Connection conn = myConnection.makeConn()
>            pstmt=conn.prepareStatement(sql);
>            pstmt.setString(1,userInfo.getPW());
>            pstmt.setString(2,userInfo.getname());
>            pstmt.setString(3,userInfo.getcode());
>            pstmt.setString(4,userInfo.getaddress());
>
>            pstmt.execute();
>        } catch (SQLException e) {
>            e.printStackTrace();
>        }
>    }
>
>    //이용자DB에 user가 등록되어있는지 유무 확인
>    public boolean isMember(String ID,String PW){
>        PreparedStatement pstmt = null;
>        String sql = null;
>        try {
>            sql="select * from "+m_table+" where ID = "+ID+" and PW = "+PW;
>            pstmt=conn.prepareStatement(sql);
>
>            //sql실행이 적용된 row의 수를 반환
>            num=pstmt.executeUpdate();
>
>            //적용된 row가 1개라도 있으면 true
>            if(num>0)
>                return true;
>
>            //없으면 false
>           else
>                return false;
>        } catch (SQLException e) {
>            e.printStackTrace();
>        }
>    }
>
>    //부모로부터 설정된 안전경로를 DB로 전송
>    public void writeSafePath(Data data){
 >       PreparedStatement pstmt = null;
>        String sql = null;
>        try {
>            sql="insert into (m_startLongitude, m_startLatitude, m_endLongitude, m_endLatitude ) " +
>                    "values (?,?,?,?)";
 >           pstmt=conn.prepareStatement(sql);
>
>            pstmt.setString(1,data.getm_startLongitude);
 >           pstmt.setString(2,data.getm_startLatitude);
>            pstmt.setString(3,data.getm_endLongitude);
  >          pstmt.setString(4,data.getm_endLatitude);
 >           pstmt.execute();
    >    } catch (SQLException e) {
   >         e.printStackTrace();
  >      }
 >   }
>
>    //부모로부터 설정된 안전경로를 DB로부터 받아옴
>    public Data readSafePath(){
>        PreparedStatement pstmt = null;
>        String sql = null;
>        Data newData= new Data();
>
>        //Safepath 테이블로부터 데이터를 가져옴
>        sql="select * from Safepath";
>        pstmt=conn.prepareStatement(sql);
>        ResultSet rs = pstmt.executeQuery();
>
>        //안전경로가 저장될 리스트
>        ArrayList<Data> safepath_list= null;
>
>        //resultSet으로부터 안전경로를 배열에 저장
>        while(!rs.hasNext())
>            safepath_list.add(rs.data);
>
>        return safepath_list;
>    }
>
>    //Data에 저장된 m_command에 따라 처리 및 결과 반환
>     public Data getResultData(char cmd, Data data){
>        switch(cmd)
>            case Data.COMMAND_CHILD_SEND_LOCATION_TO_PARENT:
>                DataSendModule.getInstance().sendDataToParent(data);
>                break;
>            case COMMAND_CHILD_SEND_LOCATION_TO_SERVER:
>                자녀 위치 정보를 DB에 저장
>                break;
>            case COMMAND_PARENT_REQUEST_FOR_LOCATION_TO_CHILD:
>                DataSendModule.getInstance().sendDataToChild(data);
>                break;
>            case xxx : yyy
>            ...
>        }
>    }
>}
>```

##4. 개발 환경
>- 윈도우 7, 윈도우 8.1, OSX
- Android Studio / Android SDK / JDK 1.8
- Tizen IDE / TIZEN SDK StandAlone Ver. 
- Linux Ubuntu / Node.js / Mysql / Samba
- Intel Pentium, Ram 2Gb 이상 급 PC
- 기어 S2

##5. 필요 기술
>- GPS Module : 자녀의 위치 정보를 얻기 위해 필요하며 자녀용 기기에 내장된 모듈이다. 위치 정보는 GPS 수신기로 3개 이상의 위성으로부터 정확한 시간과 거리를 측정하여 3개의 각각 다른 거리를 삼각 방법에 따라서 현 위치를 정확히 계산할 수 있다.
- Node.js : 서버단 애플리케이션 개발에 사용되는 소프트웨어 플랫폼이다. Node.js는 작성 언어로 자바스크립트를 활용하며 Non-blocking I/O와 단일 슬드 이벤트 루프를 통한 높은 성능을 가진다. 또한 내장 HTTP 서버 라이브러리를 포함하고 있어 웹 서버에서 아파치 등의 별도의 소프트웨어 없이 동작하는 것이 가능하며 이를 통해 웹 서버의 동작에 이어 더 많은 통제를 가능케 한다.
- Java (using Android SDK) : 보호자용 기기의 애플리케이션을 개발하기 위한 언어이다. Android는 휴대폰용 운영체제, 미들웨어, 응용프로그램을 한데 묶은 소프트웨어 플랫폼이다. 리눅스 커널을 기반으로 강력한 운영체제와 포괄적 라이브러리 세트, 풍부한 멀티미디어 인터페이스, 폰 애플리케이션 등을 제공한다.
- LTE Module : 자녀용/보호자용 기기가 서버와 통신하기 위한 이동통신 규격이다. LTE는 3G 이동통신 규격 중 유럽식 WCDMA에서 발전한 이동통신 규격이다. LTE의 전송속도는 이론적으로 다운로드 최대 75Mbps, 업로드 최대 37.5Mbps였다.
- MySQL : 서버단에서 구동되는 오픈 소스의 관계형 데이터베이스 관리 시스템(RDBMS)이다. 주요 특징은 단일 코어에서 Nested Loop join 처리, 다양한 스토리지 엔진, 데이터 복제 기능을 들 수 있다.
- Daum 지도 API : 보호자용 기기에서 자녀의 위치를 출력하기 위해 활용하는 API이다. Daum에서 무료로 제공하고 있으며 안드로이드 앱 개발 시 사용할 수 있다.
- 공공데이터 포털 API : 자녀의 안전경로를 도출하고 자녀의 안전 여부를 파악하기 위해 사용하는 API이다. 공공데이터 포털은 한국정보화진흥원에서 운영하는 공공데이터 통합제공 시스템이다. 대한민국 정부가 보유한 다양한 공공데이터를 개방하여 누구나 편리하고 손쉽게 활용할 수 있게 하는 것을 목적으로 한다.

##6. 테스트/실험 계획

|연 번|평가항목|세부평가 기준|평가점수(10)|평가의견|
|:---:|:---:|:---|----|----|
|1|자녀위치를 보호자에게 알림|· 위치 전송 후 즉시 보호자의 기기에 수신이 되는가?<br/>· 부모의 기기가 자녀의 위치 수신시 알림이 울리는가?
|2|위험한 경로 진입 알림|· 해당 경로가 위험한 경로인지 제대로 판단하는가?<br/>· 위험한 경로 진입시 알림이 울리는가?
|3|자녀가 정해진 경로를 벗어난 경우 알림|· 정해진 경로를 제대로 표현하는가?<br/>· 해당 경로가 정해진 경로가 맞는가?<br/>· 자녀가 정해진 경로 이탈시 알림이 울리는가?
|4|보호자가 실시간으로 자녀 위치를 확인|· 보호자가 자녀위치를 알고자할 때 자녀의 기기가 반응하는가?<br/>· 자녀의 기기가 전송한 위치가 보호자의 기기에서 제대로 확인되는가?
|5|전원차단, GPS 차단 시 알림|· 자녀의 기기가 전원차단 GPS차단을 제대로 감지하는가?<br/>· 전원,GPS 차단시 보호자에게 재대로 알림이 울리는가?
|6|자녀의 안전 경로를 OPEN API에 기반하여 자동으로 설정|· 자녀의 기기가 안전 경로를 제대로 수신하는가?<br/>· 안전 경로 설정이 자동으로 수신 되는가?


7. 소감
- 고현영 :  깃허브를 이용하여 협업을 할 수 있는 프로젝트를 진행해 보았습니다. 기존의 소스트리를 이용하여 깃명령어를 사용하지않고 GUI로 협업해왔으나 깃명령어로 처리하는 방법을 터특할수 있었습니다.<br/>리눅스 기반의 OS를 다루어본적이 많지 않아서 조금 어색한 감이있었지만 프로그래머가 되기위해선 리눅스 기반의 OS를 다루는 것이 많다는 얘기를 자주들어서 이번기회를 통해 조금이나마 친해질수 있는 기회였던거 같습니다.<br/>프로젝트를 진행하면서 설계를 만들 때 배운것이 많지 않아서 많은 시간이 걸렸지만 소프트웨어 공학을 배우고 있기에 지금 적용하여서 완성할수 있었던거 같습니다.
- 김재휘 : 
- 장준영 : 이번 수업을 통해 문제 정의부터 상세설계까지 새로운 시스템을 설계해보는 과정을 거쳤다. 나는 문제를 정의하고 요구사항을 정의하는 과정이 가장 어려웠다. 사용자 관점에서 요구사항을 정의해야하는데 자꾸만 개발자 관점에서 요구사항을 정의하게 되는 문제가 있었다. 기존의 시스템과 차별점을 두는 일도 만만치 않았고 설계 과정에서도 모듈을 어떻게 도출하고 어떻게 모듈 간에 상호작용하도록 할 것인지 많은 고민이 필요했다. 상세 설계하는 것도 거의 처음이어서 어디에서부터 시작해야할지 막막했다. 조원들과의 많은 대화를 통해 난관들을 하나하나 헤쳐나가서 마침내 최종 보고서까지 완성하게 되어 뿌듯하다. 이번 설계 경험을 토대로 향후 시스템 설계를 보다 수월하게 할 수 있을  것 같다.