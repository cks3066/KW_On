# Chapter 1

## Communications Network (통신망)
- Telecommunication Network 전화통신망  *[현업에선 통신망을 전화통신망으로 호칭]*
- Broadcast Network 방송통신망
- Data communication Network 데이터통신망

## 데이터의 성격
- Delivery	전달
- Accuracy	정확성
- Timeliness	시간성
- Jitter		동작 순간을 주는 타이밍 상의 편차를 지칭

## 데이터통신 시스템 구성
![화면 캡처 2021-03-19 201354](https://user-images.githubusercontent.com/62434898/111782301-322edc00-88fc-11eb-82aa-1f162cbd623d.jpg)



## 단말장치 (DTE : Date Termial Equipment)  
*[키워드 : 입출력]*
- 통신시스템과 사용자의 접점에 위치하여 데이터를 입력하거나 처리된 결과를 출력하는 장치
> 입출력제어 및 송수신 제어 기능 수행

## 신호변환장치 (DCE : Data Circuit Eqipment)  
*[키워드 : Signal Conversion]*
- 컴퓨터나 단말 장치의 데이터를 통신 회선에 적합한 신호로 변경하거나, 통신 회선의 신호를 컴퓨터나 단말장치에 적합한 신호로 변경하거나, 통신 회선의 신호를 컴퓨터나 단말 장치에 적합한 데이터로 변경하는 신호 변환 기능(Signal Converion)을 수행

## 통신제어장치 (CCU : Communication Control Unit)  
*[키워드 : Control]*
- 컴퓨터나 통신회선을 통하여 송수신되는 과정을 제어하고 감시하는 기능
> 컴퓨터의 통신제어프로그램과 통신제어장치(CCU) 구별 필요

## 데이터 통신 시스템의 특징
- 고속, 고품질의 통신서비스
- 거리와 시간의 한계 극복
- 대용량 파일의 공동 이용
- 분산 처리 방법 활용
- 시스템 신뢰도 높음	

## 자주 쓰이는 통신 용어정리
- throughput (처리량)
> 통신에서 네트워크 상의 어떤 노드나 터미널로부터 또 다른 터미널로 전달되는 단위 시간당 디지털 데이터 전송으로 처리하는 양을 말한다
- bandwidth (대역폭)
> 특정한 기능을 수행할 수 있는 주파수의 범위로, 헤르츠 단위로 측정된다.
- latency (지연시간)
> 자극과 반응 사이의 시간, 지연시간 및 응답속도라고 한다. FPS에서 중요시 되는 부분
- delay (지연)	

## Topology (망구성방식)
> 컴퓨터 네트워크의 요소들(링크, 노드 등)을 물리적으로 연결해 놓은 것, 또는 그 연결 방식
- 목적 : high throughput(bandwidth) 높은 대역폭과 처리량 & low latency 낮은 지연시간
- Mesh형, Star형, Bus형, Ring형

## Switching
인터넷은 스위치 네트워크, 패킷 교환망이다.
- circuit-switched network = telecommunication network (전화망)  *[키워드 : dedicated]*
- packet-switched network = data network (데이터망)  *[키워드 : shared]*
[써킷 교환망, 패킷 교환망 표를 만들어서 비교]

## Protocol (프로토콜)
- 정의 Syntax [구문] , Semantics [의미], Timing [순서]
 
## OSI의 7계층
 ![2](https://user-images.githubusercontent.com/62434898/111783399-88504f00-88fd-11eb-8517-1765464d17f2.jpg)
통신에 필요한 각 기능들을 각 계층별로 나누어 놓은 것
