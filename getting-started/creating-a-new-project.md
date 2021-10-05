# Creating a New Project

### **Getting Started**  시작하기

Before we begin, whilst the software is usable without them, if you wish to utilize the full capability of the Baselight system you will need a Three Button Mouse and a Full Keyboard with the Numeric Keypad. When these are needed it will be highlighted in the text but if you want to have full control it is recommended that you have both of these tools from this point.

이 섹션에서는 아래의 BarScene\(바 씬\) 이미지를 사용합니다. _generalised\_colourspaces\_v01/0\_media/0\_images/BarScene_

## Creating a New Project 새로운 프로젝트 생성하기

이 장에서는 포맷, 프로젝트 설정, 타임라인 조합, 소스 가지오기에 대해 배우고 적절한 작업 색공간, 입력 색공간, 프리뷰 색공간을 선택해야 하는 방법과 이유을 배웁니다. 이 섹션의 목표는 카메라 테스트를 위한 씬\(장면\)을 설정하고 촬영감독\(DOP\)과 연출감독이 함께 카메라 테스트 세션을 실행할 수 있도록 하는 것입니다.

1. 베이스라이트 프로그램을 엽니다. 

이렇게 하려면, 당신의 데스크탑 또는 Application &gt; Baselight 폴더에서 **베이스라이트 아이콘**을  더블 클릭하거나, !또는 리눅스 시스템의 경우, 터미널\(Terminal\)을 열고 **baselight** 라고 치고 엔터\(enter\)를 누르면 됩니다.

베이스라이트 소프트웨어는 **잡 매니저**\(Job Manager;작업관리자\)와 같이 열립니다. 잡 매니저에서는 잡과 씬을 설정할 수 있습니다. \(베이스라이트에서는 잡은 '씬'의 모음입니다. 씬의 샷의 모음이며,예를 들면, 하루치 촬영본 또는 광고나 드라마에서 컨펌본 입니다. - 이는 대본과 꼭 관련있지는 않습니다.\) UI 상단의 씬 메뉴에서 잡매니저을 열거나 키보드의 **Ctrl+J** 눌러서 엑세스 할 수 있습니다. 리눅스의 경우 **Cmd+J**.

![Image 01. &#xC0C8; &#xC791;&#xC5C5; &#xCC3D; - &#xC7A1;&#xB9E4;&#xB2C8;&#xC800;&#xAC00; &#xC774;&#xBBF8; &#xC5F4;&#xB9B0; &#xC0C1;&#xD0DC;&#xB85C; &#xBCA0;&#xC774;&#xC2A4;&#xB77C;&#xC774;&#xD2B8;&#xAC00; &#xC2DC;&#xC791;&#xB429;&#xB2C8;&#xB2E4;.](../.gitbook/assets/image.png)

Image 01. 새 작업 창 - 잡매니저가 이미 열린 상태로 베이스라이트가 시작됩니다.

잡매니저에서는 **3개의 열**을 볼 수 있습니다.

왼쪽의 **첫번째 열**은 호스트\(Host\)라고 불리웁니다. 이것은 작업 데이터베이스가 있는 위치를 나타내므로 작업중인 시스템 또는 대형 후반 제작시설의 경우 다른 베이스라이트가 될 수 있습니다. 오른쪽으로 이동하여 중간에 있는 **두번째 열**에서는 새로운 '잡'을 생성할 수 있으며,

다시 말하지만 '잡'은 다양한 씬을 담을 수 있는 프로젝트와 같습니다.

moving to the right \(middle column\) is where you can create a new ‘job’: place the arrow/mouse on this column and right-click, which will give you the option to create a New Job \(or place the mouse on the Actions menu button and click it\). Again, the job is like a project where you may keep various scenes.

The **third column**, on the far right-hand side, displays the Scenes that you have created. These will each hold collections of shots.

2 In the **Job Manager** – create a job called “camera\_test”. Click the ![](../.gitbook/assets/image%20%289%29.png) **actions** button in the second column and choose ‘New Job’. Note that once the new job is created, the software focuses on the far- right column. Now click the Actions menu button in the third column, where you can create a ‘scene’ within the job.

![ Image 02. New Scene Window - when right-clicking on the third column, a new menu opens giving the option to select &#x2018;New Scene&#x2019; \(highlighted in blue\).](../.gitbook/assets/image%20%281%29.png)

Image 02. New Scene Window - when right-clicking on the third column, a new menu opens giving the option to select ‘New Scene’ \(highlighted in blue\).

The ‘scene’ is where we set the various variables that relate to a project. The ‘job’ is really just the name of the project. The ‘job’ does not contain the variables relating to how the scene is set up. It’s the ‘scene’ that holds the important information about how the project is set up. When creating a ‘scene’ we must choose a: • Working Format \(a Resolution\) • Working Colour Space • Working Frame Rate

But the software will prompt you.

![ Image 03. The New Scene window. This is where you choose a\) Working Format, b\) Working Colour Space and c\) Working Frame Rate. See the definitions at the end of this chapter for more information.](../.gitbook/assets/image%20%288%29.png)

Image 03. The New Scene window. This is where you choose a\) **Working Format**, b\) **Working Colour Space** and c\) **Working Frame Rate**. See the definitions at the end of this chapter for more information.

3 Now that you have created a job folder, you can create a ‘scene’. You should call this “day\_1”. Note that the software is now prompting you for certain information. A general rule when setting up a scene, is to choose a wide Working Colour Space such as ACES or ARRI Log C. The Colour Space that you choose will generally not affect how the image looks but it may affect how some of the tools in Baselight react. Some tools, such as the Base Grade, have their own internal colour space so will not be affected by the Working Colour Space. We will look at Base Grade and Colour Spaces in more detail in a later section. If you are looking for a Colour Space that can be used for most situations and you are using Baselight V5, then you should use FilmLight T-Log E Gamut \(Truelight Log Extended Gamut\). If you are not using version 5, just choose a large Colour Space and if you need to understand why, take a quick look at this chromaticity diagram below.

![](../.gitbook/assets/image%20%286%29.png)

Image 04. Chromaticity Diagram.

To start to understand the significance of colour spaces look at this diagram. Notice that Rec.709 occupies a much smaller area than all of the other Colour Spaces. This is why we would not recommend Rec.709 as a Working Colour Space unless your intended project deliverables will be limited to Rec.709. A wider working space encompasses the native Colour Space of most cameras; thus, when we’re grading we’re assured we’re not losing any fidelity.

![](../.gitbook/assets/image%20%287%29.png)

Image 05. Menu with various Working Colour Spaces.

Let’s return to your setup. 4 In the new scene window select the Working Colour Space from the drop-down menu. 5 Choose FilmLight T-Log or ARRI Log C Wide Gamut.

6 Set the Working Format \(resolution\) to Film HD 1920x1080 7 Set the Working Frame Rate to 24fps. 8 Close the Job Manager window by selecting the x icon at the top right or by pressing **Ctrl+J** or **Cmd+J** on the keyboard. Once the scene is created, if you look at the top right-hand corner of the UI you will see the name of the scene and its resolution.

![](../.gitbook/assets/image%20%284%29.png)

Image 06. Scene name and resolution.

