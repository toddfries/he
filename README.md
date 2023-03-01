It took long enough to figure this out I figured
I would help others by posting this.

If you have a dynamic IP you can still do a
tunnel to he.net by scripting some changes.

Perhaps there is an easier/better/more robust way
to do some of this, feel free to provide diffs or
feedback!

Basically, you setup your hostname.em0 and hostname.gif0
per normal, then you run checkinet from cron after
populating /etc/he.conf with proper md5's from your
username and password.  Be sure to use 'echo -n "yourpassword"'
since it is a different sum than 'echo "yourpassword"' :-)

Thanks,
```
-- 
Todd Fries .. todd@fries.net .. twitter:@unix2mars .. github:toddfries

Label   | Data           | Notes
--------+----------------+------------------------------
Motto   | In support of  | free software solutions.
Phone   | 1.405.252.0702 | SMS/voice everywhere
Mobile  | 1.405.203.6124 | SMS/voice mobile only
Employer| self employed  | Free Daemon Consulting, LLC
Address | PO Box 16169   | Oklahoma City, OK 73113-2169
PGP     | 3F42004A       |
```
