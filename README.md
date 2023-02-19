<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webex Web Application</title>
    <link rel="stylesheet" href="week10.css">
</head>
<body>
    <div class = "wrapper">
        <div class = "maininterface">
            <div clss = "apptitle">
                Webex Web Application
            </div>

            <div class ="personalinfo" id="personalinfo" >

            </div>
            <div class="getpersonalbutton" id ="getpersonalbutton">
                Get Personal Info
            </div>
            <div class ="exit" id="exit">
                Exit
            </div>
            <div class="next" id="next">
                Next to Room Section
            </div>

            <div class="sendmessage" id="sendmessage">
                <form id="formid">
                    Enter Room ID:
                    <div>
                        <input type="password" id="roomid">

                    </div>
                    Enter Message :
                    <div>
                        <textarea name="" id="messageText" cols="67" rows="8">
                        </textarea>
                    </div>
                    <div>
                        <button type="submit"> Send Message</button>
                    </div>
                </form>
            </div>
            <div class="createroom" id="createroom">
                <form id="createid">
                    <b><u> CREATE A ROOM</u></b>
                    <br><br>
                    Enter Room Name:
                    <div>
                        <input type="text" id="titleid">
                    </div>
                    <div>
                        <button type="submit"> Create</button>
                    </div>
                </form>
            </div>
            <div class="invite" id="invite">
                <form id="inviteid">
                    <b><u> INVITE PEOPLE TO ROOM</u></b>
                    <br><br>
                    Enter Room ID:
                    <div>
                        <input type="password" id="roomid2">
                    </div>
                    Enter Person Email:
                    <div>
                        <input type="text" id="emailid">

                    </div>
                    <div>
                        <button type="submit">Invite</button>
                    </div>
                </form>
            </div>
            <div class="roomlist" id="roomlist">

            </div>
            <div class="getlistroombutton" id="getlistroombutton">
                Get List Room
            </div>
            <div class="back" id="back">
                Back
            </div>

            <div class="base">
                <div class="webexlogosmall">
                    <img src="logo.jpg" alt="webex" width="30" height="30">
                </div>
            </div>

            <div class="darkoverlay" id="darkoverlay">
                <div class="webexlogo" id="webexlogo">
                    <img src="logo.jpg" alt="webex" width="118" height="112">
                </div>
                <div class="accesstokenlabel" id="accesstokenlabel">
                    Access Token
                    <span class="infoicon">
                        <img src="info.png" alt="info" width="11" height="11">
                    </span>
                </div>
                <p>
                    <input type="password" class="tokeninputfield" id="tokeninputfield">

                </p>
                <div class="greenlogin" id="greenlogin">
                    Login
                </div>
            </div>
        </div>
    </div>
    <script src="week10.js"></script>
    <script src="week101.js"></script>
    <script src="week102.js"></script>
</body>
</html>
