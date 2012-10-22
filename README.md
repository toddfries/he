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
<pre>
-- 
Todd Fries .. todd@fries.net

 ____________________________________________
|                                            \  1.636.410.0632 (voice)
| Free Daemon Consulting, LLC                \  1.405.227.9094 (voice)
| http://FreeDaemonConsulting.com            \  1.866.792.3418 (FAX)
| PO Box 16169, Oklahoma City, OK 73113      \  sip:freedaemon@ekiga.net
| "..in support of free software solutions." \  sip:4052279094@ekiga.net
 \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
                                                 
              37E7 D3EB 74D0 8D66 A68D  B866 0326 204E 3F42 004A
                        http://todd.fries.net/pgp.txt
</pre>
