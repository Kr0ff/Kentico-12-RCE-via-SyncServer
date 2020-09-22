# Kentico-12-RCE-via-SyncServer
Kentico &lt;=12.0.14 is vulnerable to a remote code execution via the SyncServer.asmx.

The exploit will send a raw XML payload in an XML encoded SOAP request to a target server. The payload would then be deserialized by the Kentico CMS and executed to perform the code execution. 

Reference: https://www.aon.com/cyber-solutions/aon_cyber_labs/unauthenticated-remote-code-execution-in-kentico-cms/

Credit: @xixa
