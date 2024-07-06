Dataset:
The dataset used in this project is comprehensive and includes the following features:

Duration: The length of the connection in seconds.
Protocol Type: The type of protocol used (e.g., TCP, UDP).
Service: The network service on the destination (e.g., http, ftp).
Flag: The status of the connection (e.g., SF, REJ).
Source Bytes (src_bytes): The number of data bytes from the source to the destination.
Destination Bytes (dst_bytes): The number of data bytes from the destination to the source.
Land: A binary feature indicating if the connection is from/to the same host/port.
Wrong Fragment: The number of wrong fragments.
Urgent: The number of urgent packets.
Hot: The number of "hot" indicators.
Number of Failed Logins (num_failed_logins): The number of failed login attempts.
Logged In: A binary feature indicating if the user is logged in.
Number of Compromised (num_compromised): The number of compromised conditions.
Root Shell: A binary feature indicating if the root shell is obtained.
SU Attempted: The number of su root attempts.
Number of Root (num_root): The number of root accesses.
Number of File Creations (num_file_creations): The number of file creation operations.
Number of Shells (num_shells): The number of shell prompts.
Number of Access Files (num_access_files): The number of access control files.
Number of Outbound Commands (num_outbound_cmds): The number of outbound commands in an ftp session.
Is Host Login: A binary feature indicating if the login is from a host.
Is Guest Login: A binary feature indicating if the login is a guest login.
Count: The number of connections to the same host as the current connection in the past two seconds.
Service Count (srv_count): The number of connections to the same service as the current connection in the past two seconds.
Serror Rate (serror_rate): The percentage of connections that have SYN errors.
Service Serror Rate (srv_serror_rate): The percentage of connections that have SYN errors to the same service.
Rerror Rate (rerror_rate): The percentage of connections that have REJ errors.
Service Rerror Rate (srv_rerror_rate): The percentage of connections that have REJ errors to the same service.
Same Service Rate (same_srv_rate): The percentage of connections to the same service.
Different Service Rate (diff_srv_rate): The percentage of connections to different services.
Service Different Host Rate (srv_diff_host_rate): The percentage of connections to different hosts.
Destination Host Count (dst_host_count): The number of connections having the same destination host IP address.
Destination Host Service Count (dst_host_srv_count): The number of connections having the same destination host IP address and using the same service.
Destination Host Same Service Rate (dst_host_same_srv_rate): The percentage of connections having the same destination host IP address and using the same service.
Destination Host Different Service Rate (dst_host_diff_srv_rate): The percentage of connections having the same destination host IP address and using different services.
Destination Host Same Source Port Rate (dst_host_same_src_port_rate): The percentage of connections having the same destination host IP address and the same source port.
Destination Host Service Different Host Rate (dst_host_srv_diff_host_rate): The percentage of connections having the same destination host IP address and different host addresses.
Destination Host Serror Rate (dst_host_serror_rate): The percentage of connections having the same destination host IP address and SYN errors.
Destination Host Service Serror Rate (dst_host_srv_serror_rate): The percentage of connections having the same destination host IP address and SYN errors to the same service.
Destination Host Rerror Rate (dst_host_rerror_rate): The percentage of connections having the same destination host IP address and REJ errors.
Destination Host Service Rerror Rate (dst_host_srv_rerror_rate): The percentage of connections having the same destination host IP address and REJ errors to the same service.
Class: The label indicating if the connection is normal or anomalous.
