# CallerIDBlock

This scripts can be used in Lync Server or Skype for Business Server 2015 and allow to block PSTN calls based on the BlockedTelephoneNumbers.txt file, here is an example:

Phone,Action
<br>01234567890,block
<br>01234567891,block
<br>01234567892,block

The instalation steps can be found here:

Blocking Calls on Lync Server and Skype for Business Based on Caller ID

https://uclobby.com/2014/07/31/calleridblock/

Changelog:

<br>v1.2 - 2017-02-08:
<br>Added Event Viewer log setting
<p>v1.1 - 2016-10-04:
<br>Remove the full path reference for BlockedTelephoneNumbers.txt file;
Modified the SIP Request Filter to only process INVITEs.
<p>v1.0 – 2014-07-31:
<br>Initial release
