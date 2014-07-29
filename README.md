db_explore
==========

small mysql explorer (not secure, for use on localhost only)

!!!DO NOT USE ON THE OPEN INTERNET!!!

I made it for examining and making small changes in databases, because my installation of phpMyAdmin wasn't working properly.
Use at your own risk.

KNOWN ISSUES:
1.Connection variables stored unencrypted, in /includes/db_cfg/dbCfg.php.
2.MySQL input is not sanitized.
