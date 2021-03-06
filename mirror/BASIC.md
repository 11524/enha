![http://images02.olx.com.pe/ui/8/38/65/1280454317_107453365_1-Fotos-de
--CLASES-DE-VISUAL-BASIC-60-Y-NET-ALGORTIMOS-PROGRAMACION-ORIENTADA-A-OBJETO-E
TC-1280454317.jpg](http://images02.olx.com.pe/ui/8/38/65/1280454317_107453365_
1-Fotos-de--CLASES-DE-VISUAL-BASIC-60-Y-NET-ALGORTIMOS-PROGRAMACION-
ORIENTADA-A-OBJETO-ETC-1280454317.jpg)

[[JPG external
image]](http://images02.olx.com.pe/ui/8/38/65/1280454317_107453365_1-Fotos-de
--CLASES-DE-VISUAL-BASIC-60-Y-NET-ALGORTIMOS-PROGRAMACION-ORIENTADA-A-OBJETO-
ETC-1280454317.jpg)

  

![http://upload.wikimedia.org/wikipedia/en/6/6b/GW-
BASIC_3.23.png](http://upload.wikimedia.org/wikipedia/en/6/6b/GW-
BASIC_3.23.png)

[[PNG external image]](http://upload.wikimedia.org/wikipedia/en/6/6b/GW-
BASIC_3.23.png)

  
**B**eginner's **A**ll-purpose **S**ymbolic **I**nstruction **C**ode  

## Contents

    

1. 개요 
2. 대중성과 특징 
3. 방식 
4. 코드 예제 

[[edit](http://rigvedawiki.net/r1/wiki.php/BASIC?action=edit&section=1)]

## 1. 개요 ¶

[DOS](DOS.md)와 함께 [컴퓨터](%EC%BB%B4%ED%93%A8%ED%84%B0.md) 한번 만져본
7~80년대생이라면 **아! 그땐 그랬지**하고 무릎을 탁 칠 추억의 컴퓨터 [프로그래밍 언어](%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%96%B8%EC%96%B4.md)이다.

  

초기의 [프로그래밍언어](%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%96%B8%EC%96%B4.md)로
간단하고 또 유명한 언어. 1963년 다트머스 대학교의 존 케메니(John Kemeny)와 토머스 커츠(Thomas Kurtz)가
개발하였다. 본래는 대화형 메인프레임 시분할 언어로 설계되었으며, 퍼스널 컴퓨터에 채용됨으로써 유명해졌다. 간단한 영어의 어구를 기반으로 한
명령이 쓰이므로`[1]` 쉽게 배울 수 있다는 장점이 있으며, 이 때문에 교육용으로 널리 사용된다. 도스 마지막까지도 퍼스널 컴퓨터에서는
고급 수준 언어로 베이식이 제공되고 있었다(QBASIC).

  

[[edit](http://rigvedawiki.net/r1/wiki.php/BASIC?action=edit&section=2)]

## 2. 대중성과 특징 ¶

처음 베이식이 등장하였을 당시 빠르게 배울 수 있으며, 기존의 베이식 프로그램 문장들을 다른 프로그래머들도 쉽게 이해할 수 있고, 대부분의
운영체계에서 지원이 가능하다는 장점으로 인해 널리 퍼져나갔다.

  

8비트 시절 대부분의 PC에 롬내장 방식으로 들어가 있었다. 애플2의 경우 나중에 롬에 포함시켰다.`[2]` [IBM](IBM.md)의
퍼스널 컴퓨터인 PC 주니어에 베이식 언어를 추가하기 위한 카트리지는 1980년대 당시에 꽤나 인기있는 품목이었다고 한다. 마찬가지로 후에는
번들로 롬에 포함되었다. 간단한 시스템 제어 명령어도 있어서 나름대로 OS로 쓰이기도 했다.`[3]` <울티마1>이나 MSX의 <삼국지1>,
<대전략>`[4]` 등은 베이식으로 코딩한 게임들. 어떤 의미로는 오히려 고수일 수도...

  

재미있는 사실은 초기 IBM PC(호환기종 포함)에서 **NO ROM BASIC SYSTEM HALTED**이라는 에러 메세지가 존재
했었는데, 원인은 하드 내 파티션에 부트 영역이 존재하지 않거나 해서 도스를 부팅할 수 없을 때 나타나는 것이었다. 원래 오리지널 IBM
PC와 XT(일부 호환기종 포함)는 ROM-BASIC이라고 베이식 프로그램을 내장하고 있었고, 만약 외부 기억장치(플로피나 하드)로 부트에
실패할 경우 베이식 인터프리터 모드로 들어가게 되어 있었다. 하지만 시간이 갈수록 별 필요 없는 ROM-BASIC을 뺀 경우가 많아졌기
때문에, 이 메세지를 토해내게 된 것이다. 별 거 아니니 그냥 fdisk로 부트 영역을 재조정 해주거나 도스 디스켓을 넣으면 해결되었던
문제. 나중 시스템은 베이식을 추가할 수 없기 때문에(할 일도 없지만) 그냥 운영체제가 없다는 메시지만 나온다. 덤으로 롬에 저장된 베이식
인터프리터를 호출하는 BASIC.COM과 BASICA.COM(GWBASIC.EXE는 해당 안 된다!)을 써 본 적이 있다면 올드 프로그래머.

  

단점으로는 인터프리터 방식이 가지는 한계, 즉 처리속도가 느리다는 점을 들 수 있지만 대신 프로그램의 수정이 간단하고 외부기억장치를 필요로
하지 않는 고로 작은 시스템으로도 이용할 수 있다는 특징을 지닌다. 전용 컴파일러도 있기에 프로그램을 다 만들었다면 그냥 컴파일해서 써도
되며, 실제로도 베이식 컴파일러가 많이 나와 있다.

  

[MSX](MSX.md) 베이식, GW 베이식, 퀵 베이식, 큐베이식, 비주얼 베이식 등의 다양한 종류가 존재하며 서로 문법도 많이
차이가 난다. 서로 다른 종류 사이의 소스 코드는 거의 호환되지 않는다.

  

[마이크로소프트](%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%86%8C%ED%94%84%ED%8A%B8.md)의 [빌 게이츠](%EB%B9%8C%20%EA%B2%8C%EC%9D%B4%EC%B8%A0.md)가 본격적으로 유명해진 계기도 당시
PC 중 하나인 [알테어](%EC%95%8C%ED%85%8C%EC%96%B4.md)용 베이식 인터프리터를 만들면서였다. 알테어 광고를
보고 친구인 [폴 앨런](%ED%8F%B4%20%EC%95%A8%EB%9F%B0.md)과 함께 무작정 베이식을 팔겠다고(만들기
시작하지도 않은 상태에서) 납품제의를 했다. 승낙 후 광속의 개발을 거쳐 완성품 천공카드 묶음을 들고 본사로 가는 비행기에 탄 뒤에야 언어는
만들었는데 자신들이 만든 언어 매뉴얼을 작성해놓지 않았다는 것을 기억하고 비행기 내에서 부랴부라 매뉴얼을 작성한 <del>마감지옥</del>
이야기는 꽤 유명하다. 덤으로 약간의 디버깅도 했다고...
[천공카드](%EC%B2%9C%EA%B3%B5%EC%B9%B4%EB%93%9C.md)라 가능했던 일화. 빌 게이츠가 소프트웨어 장사를
해야겠다고 마음먹게 된 본격적인 시작도 이것. 당시 소프트웨어 저작권의 개념 자체가 없던 시절이라 매장에서 천공카드를 복사기로 무한정
복사해가는 일이 흔했는데, '이런 행동은 절도나 다름없다'고 정면으로 광고를 처음 실었던`[5]` 빌 게이츠는 당시 상당한 이야깃거리가
되었다. 하지만 당시만 해도 소프트웨어는 기업체에 납품하는 것이 기본이라 복제 배포라는 개념 자체가 거의 없었고 거의 씹혔다.

  

본격 사업가의 길을 걸은 한참 후에도 당시 만들었던 베이식 인터프리터의 소스를 거의 그대로 기억하고 있었다고. 애플의 번들 소프트였던
애플소프트 베이식도 빌 게이츠의 작품이며, MSX의 베이식도 직접 개발했다. 실제로 마이크로소프트는 베이식 언어에 대해 상당한 애정과
집착(?)을 가지고 있다. 사멸할 것이 뻔하던 베이식 언어를 비주얼 베이식이라는 걸출한 물건으로 부활시킨 뒤, 이 비주얼 베이식을
[엑셀](%EC%97%91%EC%85%80.md)에 맞게 포팅하여 [Visual Basic forApplication](Visual%20Basic%20for%20Application.md)이라는 이름으로 집어넣어놨다. 이 비주얼
베이식의 문법을 활용한 윈도우용 스크립트인 VBScript를 개발, 윈도우 뿐만 아니라 웹의 클라이언트 사이드 스크립트와 서버 사이드
스크립트로도 활용을 시도했다. 클라이언트 사이드 스크립트는
[자바스크립트](%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8.md)와의 경쟁에서
패배, 거의 사용되지 않지만`[6]`, 서버 사이드 스크립트는 잘 사용되고 있다. [ASP](ASP.md)가 바로 그것.

  

요즘에는 smallBasic이라는 교육용 베이식 언어(그러나 닷넷의 스멜이 짙어서 별로 베이식 언어답지는 않다)까지 내놓은 상태.
Visual Basic.NET은 클래스, 인터페이스 등 표준에는 없는 걸 대량으로 추가한 탓에 '베이식'이라 부르기도 애매해졌다.

  

현재는 다수의 소규모 개발사에서 개량형 버전을 내놓아 초보자들을 위한 개발 언어 및 교육용 언어로 나름대로 각광받고 있다.
<pureBasic>, <PowerBasic>, <DarkBasic>, <BlitzBasic> 등 오픈 소스 프로젝트까지 하면 종류가 엄청
많다. 게임 개발에 도전해보고 싶다면 입문 언어로 익히는 것도 좋을 듯. 다만 각자의 방식대로 OOP개념 등을 추가한 탓에 문법이 각자
다르다. 게다가 언어 자체에 버그가 상당히 창궐해서 어느 이상 복잡한 프로그램을 만들려고 들면 꼭 골치아픈 상황을 맞닥뜨리게 된다.

  

여담으로, 베이'직'이라고 읽는 경우가 많은데 실제 영어발음으로도, 외래어 표기법으로도 베이식이 올바른 표현이다. 하지만 베이식이라고 읽는
사람은 아무도 없다(...).

  

[[edit](http://rigvedawiki.net/r1/wiki.php/BASIC?action=edit&section=3)]

## 3. 방식 ¶

방식은 시대에 따라 3가지로 나뉘었다.  

  * **초기 방식**  
초기에는 실행하자마자 아무 것도 없는 화면에 몇 줄 소개만 달랑 보여주고 맨 아랫줄에는 Fn 키에 따른 명령어(해당 키를 누르면 자동입력)가
있다. 텅 빈 화면에 한 줄 코드를 입력하고 엔터를 누르면 그 코드에 따른 프로그램이 실행된다. 여러 줄로 된 프로그램을 만드려면 앞에 줄
번호 쓰고 코드를 쓴 뒤에 RUN 치면 줄 번호 순으로 코드가 실행된다. 그리고 그 줄 번호는 분기나 반복을 위해서도(GOTO 줄 번호)
쓰인다. 줄 번호 지정은 간격을 두고(대개는 10 단위) 하는 게 일반적이다. 그 이유는 나중에 코드를 추가하기 용이하도록 하기 위한
것이라고 한다. 이미 만들어진 프로그램의 코드도 수정 가능한데, 아래와 같다.  

    * 특정 줄을 바꾸려면: 바꾸려는 줄 번호를 쓰고 그 줄의 코드를 새로 작성한다. 친절하게도, 대부분은 커서를 위아래로 올리는 것이 가능해 실수로 엔터를 쳐 버렸다 할 지라도 즉시 커서를 위로 올려서 올바른 코드로 교정한 후 다시 엔터를 치면 고쳐진다.
    * 줄을 추가하려면: 추가될 줄에 맞는 번호를 쓰고(예를 들어 40번 줄과 50번 줄 사이에 추가하려면 41번~49번 중 아무거나 고르면 됨) 코드를 작성하면 된다.
    * 줄을 삭제하려면: DELETE 문에 삭제할 줄의 범위를 지정한다. 그냥 한 줄만 삭제하려면 그 줄의 번호만 쓰고 바로 엔터를 쳐도 된다.
    * 이런 식으로 수정을 계속 하다 보면 줄 번호가 어수선해지는 것은 당연지사. 이럴 땐 RENUM만 때려 주면 자동으로 해결된다.
  * **구조적 프로그래밍 방식**  
퀵 베이식이 여기에 해당한다. 시종일관 코드로 모든 작업을 해야 했던 방식에서 벗어나
[메모장](%EB%A9%94%EB%AA%A8%EC%9E%A5.md)처럼 코드를 작성하는 자체 인터페이스를 제공하였다. 이로써 줄 번호를
써가며 코딩하던 방식은 사라졌다. 그래도 초기의 방식대로 줄 번호를 매긴 코드라 할 지라도 잘 돌아간다. 다만, 학습 등의 목적이 아니면
일부러 줄 번호를 일일이 매기지는 않는다. 그리고 번호 다시 매기기도 귀찮다. <del>[RENUM도 죽었어! 더는 없어!](XXX%EB%8A%94%20%EC%A3%BD%EC%97%88%EC%96%B4%20%EC%9D%B4%EC%A0%A0%20%EC%97%86%EC%96%B4.md)</del> 이에 따라 LOAD, SAVE, LIST 등의 명령어도 사라지게 되었다. (기존의 줄번호 없이 바로 실행되던 한줄코딩은
실행창을 따로 두어서 지원하게 되었다.) 뿐만 아니라, 이때부터 베이식 언어도 발전을 하며 더 많은 명령어를 지원하는 등 많이 진보된 모습을
보여서 더 고급스러운(?) 프로그래밍이 가능해졌다. 다만 초보자 입장에서는 **들여쓰기** 문제때문에 골치아플수도 있겠다.  
[카세트 테이프](%EC%B9%B4%EC%84%B8%ED%8A%B8%20%ED%85%8C%EC%9D%B4%ED%94%84.md)에 대한
지원도 이 때쯤부터 중단되었다. 이미 훨씬 진보된 저장매체들로 대체된 지 오래고, 음원 저장용 카세트도 이미 사양길에 접어들고 있는 마당에
과연 [必要韓紙](%E5%BF%85%E8%A6%81%E9%9F%93%E7%B4%99.md)?

  * **객체 지향 방식**  
기본적으로 퀵 베이식의 구조적 프로그래밍 방식에 객체 지향 개념을 가미한 것으로 비주얼 베이식에서 사용하고 있다. 이 때부터 베이식의 예전
문법이 퇴색되기 시작하였고, 특히 Visual Basic.NET은 퇴색에 정점을 찍고 있다. 그러나 비주얼 베이식 6.0에서 가지쳐서 나온
비주얼 베이식 포 어플리케이션([Visual Basic forApplication](Visual%20Basic%20for%20Application.md), 일명 **VBA**)은 상당히 많이
쓰인다. MS 오피스와 결합된 VBA는 대단히 활용도가 높다.  

[[edit](http://rigvedawiki.net/r1/wiki.php/BASIC?action=edit&section=4)]

## 4. 코드 예제 ¶

[이곳](%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%20%EC%96%B8%EC%96%B4/%EC%BD%94%EB%93%9C%20%EC%98%88%EC%A0%9C.md)에서 볼 수 있다.

  

`\----`

  * `[1]` 이 점은 ?코볼 도 비슷하지만, 프로그램이 복잡해질수록 코드 길이가 상당히 길어지는 코볼과는 달리 이쪽은 [C](C.md)언어 와 거의 비슷한 수준.
  * `[2]` 빌게이츠가 만든 걸로도 유명한 애플소프트 베이식.
  * `[3]` 당시만 해도 OS=파일 읽을 수 있고 파일 쓸 수 있고 프로그램 실행할 수 있으면 충분 이라는 개념이었기 때문. 사실 그 이상의 기능이 필요하지도 않았다.
  * `[4]` 그래픽 처리는 기계어
  * `[5]` '취미가들에게 보내는 공개 편지'라는 이름으로 발표하였다.
  * `[6]` 표준으로 지정된 ECMAScript는 자바스크립트가 기본 베이스이다.

