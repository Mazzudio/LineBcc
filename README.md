# LineBcc
LINE Bot for send and backup image to member using google drive as storage.

<h2>Problems</h2>
An image that send or receive on LINE service has an expiration date. Sometime file cannot view or forward to others.
The solution is to backup your image before sending to others (that follow this LINE channel).
This project using LINE message API and Google Drive API to archieve.


<h2>Support command</h2>
<table>
  <tr><td>?[contentId]>>me </td><td>Recovery/Call image back.</td></tr>
  <tr><td>?[contentId]>>[userId]</td><td>Push image content that you own to user.</td></tr>
<table>

*contentId and userId will show on reply or response message from this LINE channel
