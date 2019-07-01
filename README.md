# LineBcc
LINE Bot for send and backup image to member using google drive as storage.

#Problems
An image that send or receive on LINE service has an expiration date. Sometime file cannot view or forward to others.
The solution is to backup your image before sending to others (that follow this LINE channel).
This project using LINE message API and Google Drive API to archieve.


#Support command

?[contentId]>>me        Recovery/Call image back.
?[contentId]>>[userId]  Push image content that you own to user.

*contentId and userId will show on reply or response message from this LINE channel
