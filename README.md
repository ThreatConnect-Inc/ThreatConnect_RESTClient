============================================================
  _____ _                 _    ___                      _
 |_   _| |_  _ _ ___ __ _| |_ / __|___ _ _  _ _  ___ __| |_
   | | | ' \| '_/ -_/ _` |  _| (__/ _ | ' \| ' \/ -_/ _|  _|
   |_| |_||_|_| \___\__,_|\__|\___\___|_||_|_||_\___\__|\__|
*                                                           *
============================================================

This version of Wiztools RestClient has been modified by Cyber Squared Inc.

It has been modified to accomodate the TCAuth authentication module, as 
required by the ThreatConnect API.  All distribution and reproduction of this 
tool is subject to the attached Apache 2.0 License.

The ReadMe for Wiztools RestClient is accessible at its GitHub page:
https://github.com/wiztools/rest-client

Usage of this tool is largely the same as the default RestClient, with the 
exception of the authentication process:

1.  Under the "Auth" tab, select "ThreatConnect v1" from the dropdown.
2.  In the "Access Id" box, enter your API access ID.
3.  In the "Secret Key" box, enter your Secret Key.
4.  (OPTIONAL) If you're using an On Premises/Private Cloud instance of 
    ThreatConnect which uses certificates that haven't been signed by a 
    recognized CA, under the "SSL" tab you may need to check "trust self-
    signed certificate."
5.  In the "URL" box at the top, enter the API location to test the Owners
    service (for public cloud, this is https://api.threatconnect.com/v1/owners)

For further information regarding the ThreatConnect API service and its usage, please 
consult the ThreatConnect API Documentation.

If you need any assistance with this process, please contact support@threatconnect.com.

