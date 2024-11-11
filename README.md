# Nao Robot Choregraphe Dance Project

This project contains 2 dance routines created using Choregraphe for the NAO robot. Each dance routine is saved in the ‘.pml ‘ format, which can be loaded into Choregraphe software to program the robot to perform a series of movements. 

## Files

First file: solo_jennie_take1
 -	Contains ‘solo_jennie_take1.pml' which has the dance sequence of Solo song by Jennie of Blackpink

Second file: task2_take1
  -	Contains ‘task2_take1.pml’  which has the dance sequence of 1 remix song of Watch Me (Whip/Nae Nae) by Silentó, Super Shy by NewJeans, A Thousand Years by Christina Perri, and Gangnam Style by PSY.

Use Choregraphe to open these files and deploy the dance to your NAO robot.

## The objectives of this project

-	First file focuses on the intermediate dance routines, involving synchronized body movements and song timing.
-	Second file focuses on the audience interaction and multi-song dance routine.

## Project Setup

-	Make sure you have Choregraphe installed on your computer to use the ‘.pml’ file. You can download it from the [SoftBank Robotics website](https://www.softbankrobotics.com/emea/en/nao). 
-	Choregraphe app that will be used must be preferably version of 2.8.7 and above.

## Key Configuration Details

1.	Download the two files [solo_jennie_take1 and task2_take1]
2.	Open Choregraphe app
3.	Select Open Project

![Screenshot 2024-11-09 205230](https://github.com/user-attachments/assets/aae8107d-e6c6-44c7-9069-3ce8968af3ff)

4.	Find one of the files (solo_jennie_take1.pml OR task2_take1.pml) and open it.

5.	Make sure autonomous life is switch off.

6.	Connect the stand up feature to the input button. Then save and run it. This is to make sure Nao stands up before it begins to dance.

7.	Stop the program after the robot stands up.

8.	Delete the stand up feature connection.

9. Connect the play sound, say, timeline features to the input button. Save and run it. 

 ![Screenshot 2024-11-09 205245](https://github.com/user-attachments/assets/a5dbb80d-5404-46ee-b52a-082229fa0d2f)

10. The robot will begin to dance. 

11. Stop the program after it has finished dancing.

## Troubleshooting

- **Lagging Movements**: If movements appear laggy, reduce the animation speed or simplify steps.
- **Connection Issues**: Verify NAO’s IP address and connection status.
- **Audio Sync Problems**: Check the position of the sound box in the timeline to ensure it aligns with the dance sequence. Another way is to manually reduce the movement speed to ensure it times perfectly with the song.
- **File Failed to Open**: In case of the file failed to open, check the version of Choregraphe is correct. If it is, create a new project and open project from the File section. 

## Further Customization

Users can explore Choregraphe’s additional features to add personalized gestures, sounds, and dialogues to enhance NAO’s performance. 

For questions or additional support, refer to the [Choregraphe Documentation](https://doc.aldebaran.com/).

### Group Member Contribution
- 21b4048: Done most of the dances except for Super Shy.
- 22b6002: Done the presentation, README.md file, recording, and did the Super Shy and partly SOLO dances on NAO.
