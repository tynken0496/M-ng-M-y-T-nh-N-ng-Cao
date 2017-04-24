> Nguyễn Văn Thành
> Học viện kỹ thuật mật mã

#HƯỚNG DẪN

###Menu

[1. MÔ TẢ MÔN HỌC](#1)

[2. NỘI DUNG MÔN HỌC](#2)

[3. KIẾN THỨC TIỀN ĐỀ](#3)

[4. YÊU CẦU MÔN HỌC](#4)

[5. CÁCH TIẾP CẬN NỘI DUNG MÔN HỌC](#5)

#### 1. Mô tả môn học <a name = "1"></a>

 - Chúng ta sẽ tập trung vào tầng 3(NetWork) và tầng 2(Datalink) trong mô hình OSI.
 - Tầng **network**: là nơi tìm đường đi tốt nhất cho gói tin đựa trên địa chỉ IP thông qua hoạt động của thiết bị định tuyến (router).
 <ul>
 <li>Các giao thức **định tuyến**.</li>
 <li>Các **tính năng** nâng cao.</li>
 <li>Định tuyến **BGP**.</li>
 <li>**path control** trong định tuyến.</li>
 </ul>

 - Tầng **Datalink**: là tầng liên kết dữ liệu thông qua hoạt động của thiết bị switch dựa trên địa chỉ MAC. 
 <ul>
 <li>**Switching** từ cơ bản đến nâng cao.</li>
 <li>Tính năng **bảo mật** trên hạ tầng switch</li>
 </ul>

 - **Kết thúc** khóa học, sinh viên có thể xây dụng hệ thống mạng LAN hoàn chỉnh, đáp ứng các yêu cầu của một mô hình mạng như tính **Sãn sàng**,tính **Bảo mật**, tính **dự phòng**. Bên cạnh đó là cách kết nối các LAN chi nhánh với nhau và với chi nhánh chính kết hợp internett bằng các tính năng trong các giao thức định tuyến.

#### 2. Nội dung môn học <a name="2"></a>

#####Bài 1: Tổng quan về vấn đề định tuyến

 - Tổng quan về cấu trúc của IP Header Version 4 và IP Header Version 6.
 - Từ cấu trúc trên ta có thể hiểu được tổng quan định tuyến, phân biệt định tuyến **static** cũng và định tuyến **dynamic** cũng như các khái niệm quan trọng trong định tuyến.

#####Bài 2: Giao thức định tuyến EIGRP

 - Cơ chế hoạt động của giao thức EIGRP.
 - Công thức tính metric của giao thức EIGRP.
 - Các khái niệm Unequal-cost load balacing, summary và chứng thực của giao thức EIGRP.

#####Bài 3: Giao thức định tuyến OSPF

 -  Cơ chế hoạt động của giao thức OSPF.
 -  Công thức tính metric của giao thcuws OSPF.
 -  Các khái niệm Link state database, LSA, Virtual Link, Summary, chứng thực của giao thức OSPF.

#####Bài 5: Giao thức định tuyến BGP

 - Tính chất quan trọng của BGP trong mạng lõi internet.
 - Cơ chế thiết lập neighbor.
 - Các thuộc tính quan trọng và oath selection trong BGP.

#####Bài 6: Tổng quan về switching

 - Mô hình phân lớp trong switching.
 - Địa chỉ MAC và Ethernet(802.3), Frame header.
 - Cơ chế hoạt động và cơ chế chuyển mạch của thiết bị switch.

#####Bài 7: Vlan và trunking

 - Khái niệm Vlan và các chức năng của vlan.
 - Khái niêm và tính năng của Trungking, Inter VLan-Routing và VTP.

#####Bài 8: Spanning tree protocol

 - Chức năng và cơ chế hoạt động của Spanning Tree Protocol.
 - Các dạng Spanning Tree Protocol nâng cao(PVST, RAPID STP, MST) và các cơ chế giúp ổn định Spanning Tree Protocol.

#####Bài 9: Các cơ chế dự phòng trong Switch

 - Các kỹ thuật dùng trong đảm bảo tính dự phòng trong một hệ thống như Etherchannel layer 2, Etherchannel layer 3, HSRP, VRRP, GLBP.

#####Bài 10: Các cơ chế bảo mật trên hạ tầng switching

 - Cơ chế bảo mật trên hạ tầng switching.
 - Cơ chế: Port Security, VLAN Hopping, IP source guard, Dynamic ARP Inspection, DHCP Snooping, VLAN Access Control List, xác thực Dot1x với Dynamic Vlan.

###3. Kiến thức tiền đề <a name="3"></a>

 - Môn học đòi hỏi kiến thức nền tảng về mạng máy tính, kỹ năng cấu hình máy chủ và các thiết bị mạng.

###4. Yêu cầu môn học<a name="4"></a>
 
 - Sinh viên xem trước tài liệu và làm các bài thực hành đầy đủ. Để học tốt môn này, sinh viên cần xem qua mỗi bài giảng để nắm lý thuyết và áp dụng kiến thức vào các bài thực tập.

###5. CÁCH TIẾP CẬN NỘI DUNG MÔN HỌC<a name="5"></a>

 - Để học tốt môn này, người học cần ôn tập các bài đã học, trả lời các câu hỏi và làm đầy đủ bài tập; đọc trước bài mới và tìm thêm các thông tin liên quan đến bài học. Đối với mỗi bài học, người học đọc trước mục tiêu và tóm tắt bài học, sau đó đọc nội dung bài học. Kết thúc mỗi ý của bài học, người đọc trả lời câu hỏi ôn tập và kết thúc toàn bộ bài học, người đọc làm các bài tập. 
-------------------------------------------------------------------------------



