## TBG Battle System

### System Function

We’re designed a TBG battle system. The TBG battle system allows players to select attack, defense, skills, or props at  each turn in  order to  defeat their opponents. The  system  features a range  of **customizable game characters**, each with their **own unique attributes** such as name, head portrait, attack power, defense power, and special skills. Players can select their characters using the touch screen interface, and the attributes of the selected characters are displayed on the LCD screen.

During gameplay, players can use the **touch screen to attack, defend, and use special skills against their opponents**. The system tracks the life points (HP) of each character and determines victories and defeats based on when a character's HP is equal to or less than 0. The information of victory and defeat is displayed on the LCD screen.

The  TBG  battle   system  also  includes  a  **wireless  communication  module  that  allows  for  close  range multiplayer matches**. Players can use their own miniSTM32 boards to battle against each other in real-time, with the screen of each side displaying the information of both players. The system uses a reasonable communication scheme to ensure the accuracy of the data transmitted during the online matchmaking process.

### System Design

<img src="images/system-design.png" alt="image-20240427143843364" style="zoom: 67%;" />

<img src="images/game-main-module.png" alt="image-20240427144102742" style="zoom: 25%;" />

### Results (screenshots and hardware photos)

##### (1) Game characters and attributes design + More different characters to be selected

<img src="images/result1.png" alt="image-20240427144311130" style="zoom:50%;" />

##### (2) Battle via wireless module + Touch screen operation

<img src="images/result2.png" alt="image-20240427144403101" style="zoom:50%;" />

##### (3) Winning and losing judgment

![image-20240427144506358](images/result3.png)

##### (4) More attack or defense skills for one character

<div style="display: flex; flex-wrap: wrap;">
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.016.png" alt="Image 1" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.017.png" alt="Image 2" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.018.png" alt="Image 3" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.019.png" alt="Image 4" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.012.png" alt="Image 5" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.013.png" alt="Image 6" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.014.png" alt="Image 7" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 25%; padding: 5px;">
        <img src="images/Aspose.Words.22b56b1f-ad38-48e9-b09a-7de6ab6e2ee3.015.png" alt="Image 8" style="max-width: 100%; height: auto;">
    </div>
</div>

##### (5) PvE & PvP

![image-20240427145253404](images/pvppve.png)

