|Feature|Description|Ind.|RW|EW|
|-----|-----|-----|-----|-----|
|ts|Time Stamp|+|||
|Ether_dst|Destination Media Access Control (MAC) Address|+|||
|Ether_src|Source MAC Address|+|||
|IP_src|Source Internet Protocol (IP) Address|+|||
|IP_dst|Destination IP Address|+|||
|WS_src|WireShark Source Address|+|||
|WS_dst|WireShark Destination Address|+|||
|pck_size|Packet (Frame) Size|+|||
|Ether_type|Ethernet Type|+|||
|LLC_dsap|Logical Link Control - Destination Service Access Point|+|||
|LLC_ssap|Logical Link Control - Source Service Access Point|+|||
|LLC_ctrl|Logical Link Control - Control|+|||
|EAPOL_version|Extensible Authentication Protocol (EAPOL) version|+|||
|EAPOL_type|Extensible Authentication Protocol (EAPOL) type|+|||
|EAPOL_len|Extensible Authentication Protocol (EAPOL) Length|+|||
|IP_version|IP version|+|||
|IP_ihl|IP Internet Header Length|+|||
|IP_tos|IP type of service|+|||
|IP_len|IP Length|+|||
|IP_flags|IP Flags|+|||
|IP_Z|IP Zero|+|||
|IP_MF|IP More Fragments|+|||
|IP_id|IP identifier|+|||
|IP_chksum|IP Checksum|+|||
|IP_DF|IP Don’t Fragment|+|||
|IP_frag|IP fragmentation|+|||
|IP_ttl|IP Time To Live|+|||
|IP_proto|IP Protocols|+|||
|IP_options|IP Options|+|||
|ICMP_type|Internet Control Message Protocol (ICMP) Type|+|||
|ICMP_code|ICMP Code|+|||
|ICMP_chksum|ICMP Checksum|+|||
|ICMP_id|ICMP identifier|+|||
|ICMP_seq|ICMP Sequence Number|+|||
|ICMP_ts_ori|ICMP ConditionalField     |+|||
|ICMP_ts_rx|ICMP ConditionalField     |+|||
|ICMP_ts_tx|ICMP ConditionalField     |+|||
|ICMP_ptr|ICMP ConditionalField     |+|||
|ICMP_reserved|ICMP ConditionalField     |+|||
|ICMP_length|ICMP  length|+|||
|ICMP_nexthopmtu|ICMP Next Hop Maximum Transmission Unit (MTU)|+|||
|ICMP_unused|ICMP ConditionalField     |+|||
|TCP_seq|TCP Sequence Number|+|||
|TCP_ack|TCP Acknowledgment Number|+|||
|TCP_dataofs|TCP data ofset|+|||
|TCP_reserved|TCP Reserved|+|||
|TCP_flags|TCP Flags|+|||
|TCP_FIN|FINished Flag|+|||
|TCP_SYN|Sync Flag|+|||
|TCP_RST|Reset Flag|+|||
|TCP_PSH|Push Flag|+|||
|TCP_ACK|Acknowledgment Flag|+|||
|TCP_URG|Urgent Flag|+|||
|TCP_ECE|ECE Flag|+|||
|TCP_CWR|CWR Flag|+|||
|TCP_window|TCP Window Size|+|||
|TCP_chksum|TCP Checksum|+|||
|TCP_urgptr|TCP Urgent Pointer|+|||
|TCP_options|TCP Options|+|||
|UDP_len|User datagram protocol (UDP) Length|+|||
|UDP_chksum|UDP Checksum|+|||
|DHCP_options|Dynamic Host Configuration Protocol (DHCP)  Options|+|||
|BOOTP_op|Bootstrap Protocol (BOOTP)  Options|+|||
|BOOTP_htype|BOOTP Hardware  Len  |+|||
|BOOTP_hlen|BOOTP Hardware  Length  |+|||
|BOOTP_hops|BOOTP Hardware  Options|+|||
|BOOTP_xid|BOOTP Transaction Identifier|+|||
|BOOTP_secs|BOOTP Seconds|+|||
|BOOTP_flags|BOOTP Flags|+|||
|BOOTP_sname|BOOTP Server Name|+|||
|BOOTP_file|BOOTP  Boot Filename|+|||
|BOOTP_options|BOOTP Options|+|||
|DNS_length|Domain Name System (DNS) Length|+|||
|DNS_id|DNS Identifier|+|||
|DNS_qr|DNS Query-Response|+|||
|DNS_opcode|DNS Operation Code|+|||
|DNS_aa|DNS Authoritative Answer|+|||
|DNS_tc|DNS TrunCation|+|||
|DNS_rd|DNS Recursion Desired|+|||
|DNS_ra|DNS Recursion Available|+|||
|DNS_z|DNS Reserved for future use|+|||
|DNS_ad|DNS Authentic Data|+|||
|DNS_cd|DNS Checking Disabled|+|||
|DNS_rcode|DNS Response Code |+|||
|DNS_qdcount|DNS The unsigned fields query count|+|||
|DNS_ancount|DNS Answer Count|+|||
|DNS_nscount|DNS  Authority Count|+|||
|DNS_arcount|DNS Additional Information Count|+|||
|sport_class|Source Port Class (IoTDevID classing)|+|||
|dport_class|Destination Port Class  (IoTDevID classing)|+|||
|sport23|Source Port Class ( keep wellknown ports between 0-1023)|+|||
|dport23|Destination Port Class ( keep wellknown ports between 0-1023)|+|||
|sport_bare|Source Port Number|+|||
|dport_bare|Destination Port Number|+|||
|payload_bytes|Payload size in Bytes|+|||
|entropy|Payload Entropy|+|||
|Protocol|WireShark Protocol|+|||
|sport|Source Port Number|+|||
|dport|Destination Port Number|+|||
|ID|WS_src=>WS_dst|+|||
|pck_size_mean_6|RW (Rolling windows) packet size mean  - Window size =6||+||
|pck_size_std_6|RW packet size Std. - Window size =6||+||
|ts_mean_6|RW packet time mean - Window size =6||+||
|ts_std_6|RW packet time Std.- Window size =6||+||
|TCP_window_mean_6|RW TCP Windows size mean - Window size =6||+||
|TCP_window_std_6|RW TCP Windows size Std. - Window size =6||+||
|payload_bytes_mean_6|RW Payload bytes mean - Window size =6||+||
|payload_bytes_std_6|RW Payload bytes Std. - Window size =6||+||
|entropy_mean_6|RW Entropy mean - Window size =6||+||
|entropy_std_6|RW Entropy Std. - Window size =6||+||
|pck_size_mean_9|RW (Rolling windows) packet size mean  - Window size =9||+||
|pck_size_std_9|RW packet size Std. - Window size =9||+||
|ts_mean_9|RW packet time mean - Window size =9||+||
|ts_std_9|RW packet time Std.- Window size =9||+||
|TCP_window_mean_9|RW TCP Windows size mean - Window size =9||+||
|TCP_window_std_9|RW TCP Windows size Std. - Window size =9||+||
|payload_bytes_mean_9|RW Payload bytes mean - Window size =9||+||
|payload_bytes_std_9|RW Payload bytes Std. - Window size =9||+||
|entropy_mean_9|RW Entropy mean - Window size =9||+||
|entropy_std_9|RW Entropy Std. - Window size =9||+||
|pck_size_mean_2|RW (Rolling windows) packet size mean  - Window size =2||+||
|pck_size_std_2|RW packet size Std. - Window size =2||+||
|ts_mean_2|RW packet time mean - Window size =2||+||
|ts_std_2|RW packet time Std.- Window size =2||+||
|TCP_window_mean_2|RW TCP Windows size mean - Window size =2||+||
|TCP_window_std_2|RW TCP Windows size Std. - Window size =2||+||
|payload_bytes_mean_2|RW Payload bytes mean - Window size =2||+||
|payload_bytes_std_2|RW Payload bytes Std. - Window size =2||+||
|entropy_mean_2|RW Entropy mean - Window size =2||+||
|entropy_std_2|RW Entropy Std. - Window size =2||+||
|dst_IP_diversity|Number of Destination IP (by Source IP)|||+|
|dst_port_diversity|Number of Destination Port (by Source IP)|||+|
|src_IP_diversity|Number of Source IP (by destination IP)|||+|
|IP_add_count|Number of Source IP (by destination MAC)|||+|
|pck_size_diff|the size difference of consecutive packets|||+|
|pck_size_mean_WE|EW (expanding windows) packet size mean|||+|
|pck_size_std_WE|EW packet size Std.|||+|
|pck_size_sum_of_EW|EW packet size total.|||+|
|ts_diff|the time difference of consecutive packets|||+|
|ts_mean_WE|EW packet time mean|||+|
|ts_std_WE|EW packet time Std.|||+|
|ts_sum_of_EW|EW packet time total.|||+|
|TCP_window_diff|TCP Windows size difference of consecutive packets|||+|
|TCP_window_mean_WE|EW TCP Windows size mean|||+|
|TCP_window_std_WE|EW TCP Windows size Std.|||+|
|TCP_window_sum_of_EW|EW TCP Windows size total.|||+|
|payload_bytes_diff|Payload bytes difference of consecutive packets|||+|
|payload_bytes_mean_WE|EW Payload bytes mean|||+|
|payload_bytes_std_WE|EW Payload bytes Std.|||+|
|payload_bytes_sum_of_EW|EW Payload bytes total.|||+|
|entropy_diff|Entropy difference of consecutive packets|||+|
|entropy_mean_WE|EW Entropy mean|||+|
|entropy_std_WE|EW Entropy Std.|||+|
|entropy_sum_of_EW|EW Entropy total.|||+|
|dport_sum|EW Unique destination port number|||+|
|sport_sum|EW Unique source port number|||+|
|TCP_FIN_sum|EW FINished Flag|||+|
|TCP_SYN_sum|EW Sync Flag|||+|
|TCP_RST_sum|EW Reset Flag|||+|
|TCP_PSH_sum|EW Push Flag|||+|
|TCP_ACK_sum|EW Acknowledgment Flag|||+|
|TCP_URG_sum|EW Urgent Flag|||+|
|TCP_ECE_sum|EW ECE Flag|||+|
|TCP_CWR_sum|EW CWR Flag|||+|
|TCP_FIN_ratio|TCP_FIN/TCP_FIN_sum|||+|
|TCP_SYN_ratio|TCP_SYN/TCP_SYN_sum|||+|
|TCP_RST_ratio|TCP_RST/TCP_RST_sum|||+|
|TCP_PSH_ratio|TCP_PSH/TCP_PSH_sum|||+|
|TCP_ACK_ratio|TCP_ACK/TCP_ACK_sum|||+|
|TCP_URG_ratio|TCP_URG/TCP_URG_sum|||+|
|TCP_ECE_ratio|TCP_ECE/TCP_ECE_sum|||+|
|TCP_CWR_ratio|TCP_CWR/TCP_CWR_sum|||+|
|sum|EW all TCP Flags|||+|
|TCP_FIN_SR|TCP_FIN/sum|||+|
|TCP_SYN_SR|TCP_SYN/sum|||+|
|TCP_RST_SR|TCP_RST/sum|||+|
|TCP_PSH_SR|TCP_PSH/sum|||+|
|TCP_ACK_SR|TCP_ACK/sum|||+|
|TCP_URG_SR|TCP_URG/sum|||+|
|TCP_ECE_SR|TCP_ECE/sum|||+|
|TCP_CWR_SR|TCP_CWR/sum|||+|
|TCP_FIN_R|TCP_FIN_sum/sum|||+|
|TCP_SYN_R|TCP_SYN_sum/sum|||+|
|TCP_RST_R|TCP_RST_sum/sum|||+|
|TCP_PSH_R|TCP_PSH_sum/sum|||+|
|TCP_ACK_R|TCP_ACK_sum/sum|||+|
|TCP_URG_R|TCP_URG_sum/sum|||+|
|TCP_ECE_R|TCP_ECE_sum/sum|||+|
|TCP_CWR_R|TCP_CWR_sum/sum|||+|
|Label|Packet Level Label|+|||