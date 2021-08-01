# CryptoBlades-Stamina-Reminder
A simple Google Sheet reminder for CryptoBlades Stamina using Google App Script.

How to Setup in your Google Account to avoid #ERROR
1. open the google sheet link : https://docs.google.com/spreadsheets/d/1dEoCj4R6eNjPXwhPuw5XVMVh-nJuN74FM79QNlSakvk/edit?usp=sharing

![image](https://user-images.githubusercontent.com/15312428/127759554-a49676cf-c365-4ab1-b24a-47f2101c284f.png)

2. Make a Copy beacase you can't edit my google sheet.
![image](https://user-images.githubusercontent.com/15312428/127759616-25e95cee-870d-44dd-9006-5a4b29828161.png)

3. Rename and Saved to your drive by clicking OK button, and it will open your copy.
![image](https://user-images.githubusercontent.com/15312428/127759625-64397c98-179c-401a-be91-be20556477e9.png)

4. Notice the #ERROR! under the Value, this means that you need to allow permission to access the script.
![image](https://user-images.githubusercontent.com/15312428/127759665-572cb088-2d2c-418c-99aa-592bbd2e2988.png)

5. Under Tools, Click Script Editor, It will open new tab
![image](https://user-images.githubusercontent.com/15312428/127759688-c135def8-7ac4-4c2b-858a-6e39d6f27bf0.png)

6.Click Run and Review permission, If the dialog box doesn't appear, close the tab and repeat step 5.
![image](https://user-images.githubusercontent.com/15312428/127759759-54b1dcba-eacf-4e07-8824-9e3ab83f4d9e.png)

7. Click the account you want to have access. make sure to choose same account in your current browser.
![image](https://user-images.githubusercontent.com/15312428/127759807-3d14ba10-1ed5-4b45-9a26-3f1bcfd577aa.png)

8. Google will promt a warning, Just Click Advanced then..
![image](https://user-images.githubusercontent.com/15312428/127759841-600b80ea-ec40-44c2-9776-c73cb0af5c0b.png)

Click the "Go to....(Unsafe) and click Allow button
![image](https://user-images.githubusercontent.com/15312428/127759858-46b83245-4fca-4337-868f-681049fed431.png)

9. Remove the "m" under Library >... > Remove > and click Remove Library
![image](https://user-images.githubusercontent.com/15312428/127759898-8dd7af5e-13cc-447d-9962-4f2987f34cfd.png)

10. Add new Library by clicking + sign. You need to get "Script ID*" so click cancel then go to step 11.
![image](https://user-images.githubusercontent.com/15312428/127759929-7efea5c2-037b-47f9-b92b-03dba08bab5c.png)

11. Under Project Settings, Click the Copy Icon to get the Script ID.
![image](https://user-images.githubusercontent.com/15312428/127759968-5e30c1b3-4a29-4754-8924-7aff0a1e8753.png)

12. Go back to the Editor, then add Library, paste the Script ID. click Lookup > Click Add button
![image](https://user-images.githubusercontent.com/15312428/127759992-0c7937c0-bec7-428f-b665-9091329d1832.png)
![image](https://user-images.githubusercontent.com/15312428/127760015-9359e399-a486-4720-a448-9e2ea26a1e56.png)

13. Click Run, and wait.. you must see Logs same in the picture below.
![image](https://user-images.githubusercontent.com/15312428/127760035-db64171f-2887-4643-9107-010cdabece61.png)

14. Now, We will add Trigger to run the script continuosly.
![image](https://user-images.githubusercontent.com/15312428/127760068-8e3e2f48-77e8-4ecc-907d-2b2d031f6890.png)

15. Choose theTime-driven and Every minute Interval , then click save.
![image](https://user-images.githubusercontent.com/15312428/127760092-ba5cd4d7-b559-435b-afba-9be083bc9e0f.png)

16. Go back to your Google sheet copy. and "#ERROR" should disappear.
![image](https://user-images.githubusercontent.com/15312428/127760148-16353e67-37ad-480b-82ca-210a021c9e57.png)

17. You can now set up reminder: Guide on how to use the reminder is on youtube: https://youtu.be/D2kBA5Scd0c



