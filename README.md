INSERT INTO Brands (BrandID, BrandName) VALUES 
(1, 'Nhã Nam'), 
(2, 'NXB Trẻ'), 
(3, 'Thái Hà Books'), 
(4, 'Skybooks'), 
(5, 'First News'); 

INSERT INTO Accounts (AccountID, Username, FullName, Password, Email, Phone, 
Address, AccountType) VALUES 
(1, 'tainguyen123', 'Nguyễn Văn Tài', '123456789', 'tainguyen123@gmail.com', 
'912345678', '123 Nguyễn Trãi, Q.1, TP.HCM', 'consumer'), 
(2, 'lehoai456', 'Lê Thị Hoài', 'abcdef1234', 'lehoai456@gmail.com', '987654321', '456 Hai 
Bà Trưng, Q.3, TP.HCM', 'consumer'), 
(3, 'tranvan789', 'Trần Văn An', 'qwerty1234', 'tranvan789@gmail.com', '901234567', '789 
Lê Văn Quới, Q. Bình Tân, TP.HCM', 'consumer'), 
(4, 'hoangthi123', 'Hoàng Thị Mai', '1234567890', 'hoangthi123@gmail.com', '934567890', 
'123 Phan Văn Trị, Q. Gò Vấp, TP.HCM', 'consumer'), 
(5, 'nguyenthanh456', 'Nguyễn Thanh Bình', 'abcdef12345', 'nguyenthanh456@gmail.com', 
'9876543210', '456 Phạm Văn Chí, Q. Tân Bình, TP.HCM', 'consumer'), 
(6, 'lehoang789', 'Lê Hoàng Long', 'qwerty123456', 'lehoang789@gmail.com', 
'9012345678', '789 Nguyễn Đình Chiểu, Q. Phú Nhuận, TP.HCM', 'consumer'), 
(7, 'tranthithuy123', 'Trần Thị Thuý', '12345678901', 'tranthithuy123@gmail.com', 
'9345678901', '123 Võ Văn Tần, Q.3, TP.HCM', 'consumer'), 
(8, 'hoangminh456', 'Hoàng Minh Tuấn', 'abcdef1234567', 'hoangminh456@gmail.com', 
'98765432109', '456 Trần Hưng Đạo, Q.1, TP.HCM', 'consumer'), 
(9, 'nguyenthuy789', 'Nguyễn Thuý Hằng', 'qwerty12345678', 
 'nguyenthuy789@gmail.com', '90123456789', '789 Nguyễn Huệ, Q. Tân Bình, TP.HCM', 
'consumer'), 
(10, 'leminh123', 'Lê Minh Quang', '123456789012', 'leminh123@gmail.com', 
 '93456789012', '123 Cách Mạng Tháng Tám, Q.10, TP.HCM', 'consumer'), 
(11, 'Fahasa', 'Công ty Cổ phần Sách Fahasa', 'shopA123', 'Fahasa@gmail.com', 
'901234567', '123 Nguyễn Trãi, Hà Nội', 'seller'), 
(12, 'Kim Đồng', 'Nhà xuất bản Kim Đồng', 'shopB456', 'Kimdong@gmail.com', 
'987654321', '456 Hai Bà Trưng, TP.HCM', 'seller'), 
(13, 'Tiến Thọ', 'Công ty Cổ phần Sách Tiến Thọ', 'shopC789', 'Tientho@gmail.com', 
'909876543', '789 Phan Đình Phùng, Đà Nẵng', 'seller'), 
(14, 'Ngon Books', 'Công ty TNHH Sách Ngon', 'shopD1011', 'Ngonbooks@gmail.com', 
'909876468', '1000 Trần Duy Hưng, Hà Nội', 'seller'), 
(15, 'Đinh Tường', 'Công ty Cổ phần Sách Đinh Tường', 'shopE1213', 
'Dinhtuong@gmail.com', '909876548', '1200 Hai Bà Trưng, TP.HCM', 'seller'), 
(16, 'Bookworm', 'Cửa hàng sách Bookworm', 'shopF1415', 'Bookworm@gmail.com', 
'909876555', '1400 Phan Đình Phùng, Đà Nẵng', 'seller'), 
(17, 'Phạm Văn Chân', 'Nhà sách Phạm Văn Chân', 'shopG1617', 
'Phamvanchan@gmail.com', '909876589', '1600 Trần Duy Hưng, Hà Nội', 'seller'),  
(18, 'Eureka', 'Sách Eureka', 'shopH1819', 'Eureka@gmail.com', '909876578', '1800 Hai Bà 
Trưng, TP.HCM', 'seller'), 
(19, 'Mọt Sách', 'Cộng đồng Mọt Sách', 'shopI2021', 'Motsach@gmail.com', '909876541', 
'2000 Phan Đình Phùng, Đà Nẵng', 'seller'), 
(20, 'Tiki Books', 'Tiki Trading Co., Ltd.', 'shopJ2223', 'Tikibooks@gmail.com', 
'909876574', '2200 Trần Duy Hưng, Hà Nội', 'seller'); 

INSERT INTO Consumers (ConsumerID, AccountID) VALUES 
(1, 1), 
(2, 2), 
(3, 3), 
(4, 4), 
(5, 5), 
(6, 6), 
(7, 7), 
(8, 8), 
(9, 9), 
(10, 10); 

INSERT INTO Sellers (SellerID, AccountID) VALUES 
(1, 11), 
(2, 12), 
(3, 13), 
(4, 14), 
(5, 15), 
(6, 16), 
(7, 17), 
(8, 18), 
(9, 19), 
(10, 20); 

INSERT INTO Products (ProductID , BrandID, SellerID, ProductName, QuantityInStock, 
UnitPrice, Origin, Description, Image) VALUES 
(1, 1, 1, 'Cây Cam Ngọt Của Tôi', 1250, 78900, 'Việt Nam', 'Mở đầu bằng những thanh âm 
trong sáng và kết thúc lắng lại trong những nốt trầm hoài niệm, Cây cam ngọt của tôi khiến 
ta nhận ra vẻ đẹp thực sự của cuộc sống đến từ những điều giản dị như bông hoa trắng của 
cái cây sau nhà, và rằng cuộc đời thật khốn khổ nếu thiếu đi lòng yêu thương và niềm trắc 
ẩn. Cuốn sách kinh điển này bởi thế không ngừng khiến trái tim người đọc khắp thế giới thổn thức, 
kể từ khi ra mắt lần đầu năm 1968 tại Brazil.', 'https://salt.tikicdn.com/cache/750x750/ts/product/5e/18/24/2a6154ba08df6ce6161c13f43 03fa19e.jpg.webp'), 
(2, 1, 1, 'Những Tù Nhân Của Địa Lý', 1150, 161700, 'Việt Nam', 'Sách cung cấp cái nhìn 
sâu sắc và chi tiết về địa chính trị toàn cầu và góc nhìn chuyên sâu và sáng suốt từ tác giả 
có kinh nghiệm. Được đánh giá cao bởi giới phê bình và nằm trong danh sách bán chạy của The New York Times.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/8d/96/9e/c0c1f23db756d50b1944dff9c
 3988753.jpg.webp'), 
(3, 1, 1,'Nhà Giả Kim (Tái Bản 2020)', 1750, 47400, 'Việt Nam', 'Tiểu thuyết Nhà giả kim 
của Paulo Coelho như một câu chuyện cổ tích giản dị, nhân ái, giàu chất thơ, thấm đẫm 
những minh triết huyền bí của phương Đông. Trong lần xuất bản đầu tiên tại Brazil vào 
năm 1988, sách chỉ bán được 900 bản. Nhưng, với số phận đặc biệt của cuốn sách dành 
cho toàn nhân loại, vượt ra ngoài biên giới quốc gia, Nhà giả kim đã làm rung động hàng 
triệu tâm hồn, trở thành một trong những cuốn sách bán chạy nhất mọi thời đại, và có thể 
làm thay đổi cuộc đời người đọc.', 'https://salt.tikicdn.com/cache/750x750/ts/product/45/3b/fc/aa81d0a534b45706ae1eee1e3
 44e80d9.jpg.webp'), 
(4, 1, 1,'Một Thoáng Ta Rực Rỡ Ở Nhân Gian', 1350, 94400, 'Việt Nam', 'Một thoáng ta 
rực rỡ ở nhân gian viết dưới dạng một lá thư của nhân vật chính, Chó Con, gửi cho người 
mẹ không biết chữ của mình. Dưới dạng những mẩu chuyện nhỏ, xen kẽ với những đoạn 
trữ tình ngoại đề, triết lý, và những bài thơ, cuốn sách kể câu chuyện đời không chỉ của 
Chó Con (tên gọi yêu do bà ngoại đặt cho, nhưng cũng là cách tất cả mọi người trong sách 
gọi cậu) từ thuở nhỏ đến lúc chớm trưởng thành, mà cả ba thế hệ từ bà, đến mẹ, đến cậu, 
một cuộc di cư dài từ làng quê Việt Nam sang đất Mỹ, cũng như câu chuyện của những 
thanh niên Mỹ thế hệ cậu mà đặc trưng là người bạn trai Trevor.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/2f/b5/4e/a8208e9019c8510e8a8eebe06
 f50299c.jpg.webp'), 
(5, 1, 2,'Yêu Những Điều Không Hoàn Hảo', 1150, 88900, 'Việt Nam', 'Sách Viết bởi nhà 
giảng và nhà tâm lý học uy tín. Cung cấp câu chuyện và triết lý thú vị về tình yêu và chấp  nhận.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/20/79/b3/8b1139ce30144b41473b199c
 19001942.jpg.webp'), 
(6, 1, 2,'Xứ Cát', 1150, 174000, 'Việt Nam', 'Là một trong những cuốn tiểu thuyết khoa học 
giả tưởng bán chạy nhất mọi thời đại, Xứ Cát không chỉ là lựa chọn đối với những tín đồ 
của Chúa nhẫn, Chiến tranh giữa các vì sao… mà còn chinh phục độc giả đủ mọi lứa tuổi, 
mọi tầng lớp và sở thích bởi sự đa dạng và phức tạp của con người và không gian trong 
truyện, bởi sự tinh tế trong xây dựng tâm lý, bởi sự hấp dẫn, căng thẳng và bất ngờ của cốt 
truyện, bởi sự độc đáo và thú vị của khối lượng kiến thức khổng lồ cũng như bởi sự hấp 
dẫn trong những tư tưởng về tôn giáo, về tự do, về tình yêu, về sự sống và cái chết…', 
'https://salt.tikicdn.com/cache/750x750/ts/product/b4/f0/81/5d5e4a26cb029fdecd04e0c30
 cbef17a.jpg.webp'), 
(7, 1, 2,'Sự Im Lặng Của Bầy Cừu (Tái Bản)', 1000, 69000, 'Việt Nam', 'Sự im lặng của 
bầy cừu hội tụ đầy đủ những yếu tố làm nên một cuốn tiểu thuyết trinh thám kinh dị xuất 
sắc nhất: không một dấu vết lúng túng trong những chi tiết thuộc lĩnh vực chuyên môn, với 
các tình tiết giật gân, cái chết luôn lơ lửng, với cuộc so găng của những bộ óc lớn mà không 
có chỗ cho kẻ ngu ngốc để cuộc chơi trí tuệ trở nên dễ dàng. Bồi đắp vào cốt truyện lôi 
cuốn đó là cơ hội được trải nghiệm trong trí não của cả kẻ gây tội lẫn kẻ thi hành công lý, 
khi mỗi bên phải vật vã trong ngục tù của đau đớn để tìm kiếm, khẩn thiết và liên tục, một 
sự lắng dịu cho tâm hồn.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/cd/2a/5b/926ca6c7b295c6e7cea39390e
 fe08968.jpg.webp'), 
(8, 1, 2,'Phía Sau Nghi Can X (Tái Bản 2019)', 1000, 81700, 'Việt Nam', 'Với một giọng 
văn tỉnh táo và dung dị, Higashino Keigo đã đem đến cho độc giả hơn cả một cuốn tiểu 
thuyết trinh thám. Mô tả tội ác không phải điều hấp dẫn nhất ở đây, mà còn là những giằng 
xé nội tâm thầm kín, những nhân vật bình dị, và sự quan tâm sâu sa tới con người. Tác 
phẩm đã đem lại cho Higashino Keigo Giải Naoki lần thứ 134, một giải thưởng văn học lâu 
đời sánh ngang giải Akutagawa tại Nhật.', 'https://salt.tikicdn.com/cache/750x750/ts/product/23/56/86/a538698ead7dc2f693d1e977
 8417317d.jpg.webp'), 
(9, 2, 3,'Như Cơn Gió Thoảng - Nghĩ Về Những Qui Luật Cuộc Sống', 1240, 107000, 'Việt 
 Nam', 'Dưới góc nhìn của một nhà khoa học mang tinh thần Phật giáo, những vấn đề vốn 
chủ quan và cảm tính đều được tác giả nhìn dưới góc độ khoa học với lối viết dễ hiểu, dễ 
cảm và đáng tin cậy. Đồng thời những bài viết ấy cũng sâu sắc và tự nhiên với cái nhìn thế 
sự như gió thoảng mây trôi bỗng chốc hóa vô thường. Bàng bạc trong cả tác phẩm là một 
thái độ bình thản đối diện, trút bỏ mọi ảo vọng ở đời để giữ vững ý chí và không quên tâm 
nguyện thuở ban đầu.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/0b/34/53/ceb30ecdb1929dfade8d3213
 736aa44a.jpg.webp'), 
(10, 2, 3,'Xa Ngoài Kia Nơi Loài Tôm Hát - Where The Crawdads Sing', 1050, 133000, 
'Việt Nam', 'Trong nhiều năm, những tin đồn về "Cô gái đầm lầy" đã ám ảnh Barkley Cove, 
một thị trấn yên tĩnh trên bờ biển Bắc Carolina. Vì vậy, khi nơi này rúng động với cái chết 
đầy bí ẩn của Chase Andrew, người dân địa phương ngay lập tức đổ dồn nghi ngờ vào cô.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/9a/df/6d/0c3ad2b36f781ea61a47828a0
 4db71a0.jpg.webp'), 
(11, 2, 3,'Đời Ngắn Đừng Ngủ Dài (Tái Bản)', 1450, 52200, 'Việt Nam', 'Bằng những lời 
chia sẻ thật ngắn gọn, dễ hiểu về những trải nghiệm và suy ngẫm trong đời, Robin Sharma 
tiếp tục phong cách viết của ông từ cuốn sách Điều vĩ đại đời thường để mang đến cho độc 
giả những bài viết như lời tâm sự, vừa chân thành vừa sâu sắc.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/57/44/86/19de0644beef19b9b885d094
 2f7d6f25.jpg.webp'), 
(12, 2, 3,'Từ Tốt Đến Vĩ Đại (Tái bản 2021)', 1350, 67500, 'Việt Nam', 'Mỗi kết luận của 
nhóm nghiên cứu đều hữu ích, vượt thời gian, ý nghĩa vô cùng to lớn đối với mọi lãnh đạo 
và quản lý ở mọi loại hình công ty (từ công ty có nền tảng và xuất phát tốt đến những công 
ty mới khởi nghiệp), và mọi lĩnh vực ngành nghề. Đây là cuốn sách nên đọc đối với bất kỳ 
lãnh đạo hay quản lý nào!', 
'https://salt.tikicdn.com/cache/750x750/ts/product/84/f5/a2/8cd3d96f65304037a1f038c98
 2e718e9.jpg.webp'), 
(13, 2, 4,'Suối Nguồn (Tái Bản)', 1250, 302000, 'Việt Nam', 'Có rất ít cột chỉ đường trong 
cuộc tìm kiếm này. Suối nguồn là một trong những cột chỉ đường đó. Đây chính là một 
trong những lý do cơ bản nhất khiến cho suối nguồn có sức hấp dẫn lâu dài; nó tái khẳng 
định tinh thần của tuổi trẻ, nó tuyên bố về chiến thắng của con người, nó chỉ ra người ta có 
thể làm được những gì.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/4b/8b/7b/a50779f09d8ea83a225d2048
 e583a73b.jpg.webp'), 
(14, 2, 4,'Nhà Lãnh Đạo Không Chức Danh', 1250, 73400, 'Việt Nam', 'Suốt hơn 15 năm, 
Robin Sharma đã thầm lặng chia sẻ với những công ty trong danh sách Fortune 500 và 
nhiều người siêu giàu khác một công thức thành công đã giúp ông trở thành một trong 
những nhà cố vấn lãnh đạo được theo đuổi nhiều nhất thế giới. Đây là lần đầu tiên Sharma 
công bố công thức độc quyền này với bạn, để bạn có thể đạt được những gì tốt nhất, đồng 
thời giúp tổ chức của bạn có thể có những bước đột phá đến một cấp độ thành công mới 
trong thời đại thiên biến vạn hóa như hiện nay.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/1d/42/93/242e97bbff16afc192f1976e3
 bdf5f19.jpg.webp'), 
(15, 2, 4,'Ngày Xưa Có Một Con Bò…(Tái Bản)', 1150, 46900, 'Việt Nam', 'Khởi đầu bằng 
một câu chuyện mang tính ngụ ngôn vừa ngắn gọn, vừa dễ hiểu, cuốn sách rút ra một bài 
học sâu sắc nhưng thật đơn giản cho những ai vẫn đang vật lộn tìm kiếm thành công ở đời: 
những lời bao biện, viện cớ, đổ lỗi chẳng bao giờ giúp được chúng ta thành công hơn; 
ngược lại, dám dũng cảm đối mặt với sự trì trệ của mình để sẵn sàng tìm ra giải pháp mới 
là con đường tiến lên bền vững.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/47/79/a4/0fccd2940cffa207e35102552
 99d8ecf.jpg.webp'), 
(16, 2, 4,'Tiếp Thị 5.0: Công Nghệ Vị Nhân Sinh', 1050, 82400, 'Việt Nam', 'Cuốn sách 
này hoàn hảo dành cho các nhà tiếp thị truyền thống và tiếp thị số, sinh viên cũng như 
giảng viên tiếp thị và kinh doanh. Tiếp thị 5.0 đã truyền một luồng sinh khí mới cho ngành 
tiếp thị với những đề xuất hữu ích và cái nhìn độc đáo.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/8a/9b/2e/78227a90089e080276831d7c
 80397a28.jpg.webp'), 
(17, 3, 5,'Cơ Thể Ta Đã Hai Triệu Năm - Giải Mã Các Căn Bệnh Thời Hiện Đại', 1220, 
63200, 'Việt Nam', 'Qua cuốn sách “Cơ thể ta đã hai triệu năm – Giải mã các căn bệnh thời 
hiện đại”, chúng ta sẽ cùng nhau tìm hiểu và nhận biết những cơ chế thích nghi nguyên 
thủy của con người. Từ đó đưa ra những thay đổi trong chế độ ăn, thói quen sinh hoạt để 
điều chỉnh những cơ chế này cho phù hợp với đời sống hiện đại cũng như đem lại lợi ích 
sức khỏe tối đa.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/18/4b/0d/a58be739890f5d5db528dda4
 e6333a7f.jpg.webp'), 
(18, 3, 5,'Power Vs Force - Trường Năng Lượng Và Những Nhân Tố Quyết Định Hành Vi 
Của Con Người (Tái Bản)', 1450, 122000, 'Việt Nam', 'Cuốn sách này đã đem đến một 
bước đột phá lớn lao cho tinh thần con người, phác ra những chiều kích ý thức mà trước 
đây chỉ những người có khả năng thần bí mới biết tới. Những con người có thiên khiếu trực 
nhận Thực tại (hay cách gọi gì chăng nữa) như thế, luôn luôn khẳng định vai trò trung tâm 
của cái “vô hình”.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/37/54/79/b699efce8c0f4029f424019f5
 61ef327.png.webp'), 
(19, 3, 5,'Kiếp Nào Ta Cũng Tìm Thấy Nhau: Câu Chuyện Về Những Linh Hồn Tri Kỷ 
Vĩnh Viễn Không Chia Lìa (Tái Bản)', 1500, 67200, 'Việt Nam', 'Kiếp nào ta cũng tìm thấy 
nhau là cuốn sách thứ ba của Brain L. Weiss – một nhà tâm thần học có tiếng. Trước đó  
làm ông đã viết hai cuốn sách: cuốn đầu tiên là Ám ảnh từ kiếp trước, cuốn sách mô tả câu 
chuyện có thật về một bệnh nhân trẻ tuổi cùng với những liệu pháp thôi miên về kiếp trước 
đã thay đổi cả cuộc đời tác giả lẫn cô ấy.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/b6/1a/8f/6b64314b3676754e69c7bdeb
 1004e26a.jpg.webp'), 
(20, 3, 5,'Sự Trung Thực Của Xác Chết – Ghi Chép Của Một Nhà Pháp Y', 1400, 71200, 
'Việt Nam', 'Với kinh nghiệm 20 năm trong ngành, Hajime Nishio đã thực hiện không ít 
các cuộc giải phẫu thi thể. Tác giả thường phải đối diện với rất nhiều sự đau đớn, khổ sở 
không nói nên lời của người đã và đang sống trong xã hội Nhật Bản. Thông qua Sự trung 
thực của xác chết, ông còn muốn truyền tải đến độc giả những “khác biệt” mà mình đã 
được chứng kiến từ những thi thể ấy', 
'https://salt.tikicdn.com/cache/750x750/ts/product/f4/bc/14/c202a8b6953aebc2a4f38696a
 ea7241e.jpg.webp'), 
(21, 3, 6,'Chiến Thắng Con Quỷ Trong Bạn - Bí Quyết Tự Do Và Thành Công (Tái Bản)', 
1650, 78100, 'Việt Nam', 'Cuốn sách là cuộc trò chuyện của Napoleon Hill và Con Quỷ. 
Sau bao nhiêu năm miệt mài nghiên cứu cuối cùng ông cũng phát hiện ra Con Quỷ, bắt nó 
phải thú tội và tiết lộ những sự thật kinh hoàng về nơi nó sống, cách nó kiểm soát tâm trí 
con người và cách để con người chiến thắng được nó. Khi đọc cuốn sách này, có thể bạn 
sẽ tự hỏi, cuộc trò chuyện này có thật không?', 
'https://salt.tikicdn.com/cache/750x750/ts/product/bb/90/07/04472bee8e62705b145ea4a4
 d5f1736f.jpg.webp'), 
(22, 3, 6,'Bàn Về Ham Muốn: Tại Sao Chúng Ta Muốn Thứ Mà Ta Muốn', 1540, 122000, 
'Việt Nam', 'Đọc “Bàn về ham muốn” có thể giúp bạn để tâm đến sự vận hành của ham 
muốn trong mình. Khi đó, bạn sẽ nhanh chóng có nhận thức đầy kinh ngạc rằng ham muốn 
của bạn có một cuộc đời riêng. Chúng chợt lóe lên trong đầu bạn, gần như là từ trên trời 
rơi xuống. Thực sự, trong nhiều trường hợp, bạn không lựa chọn những ham muốn của 
mình nhiều bằng việc phát hiện thấy chúng tồn tại trong bạn. Bạn cũng sẽ hiểu rõ mức độ 
về dài mà những ham muốn không mời mà đến này định đoạt cách mà bạn sống mỗi ngày và về 
lâu là cách mà bạn sống hết cuộc đời mình.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/ec/0d/db/881ef8e65256f339b31a35ae0
 3c5de75.jpg.webp'), 
(23, 3, 6,'Ám Ảnh Từ Kiếp Trước - Bí Mật Của Sự Sống Và Cái Chết (Tái Bản 2020)', 
1530, 60729, 'Việt Nam', 'Cuốn sách hay và khiêu khích suy nghĩ này đã phá vở những rào 
cản trong trị liệu tâm lý truyền thống và trình bày một biện pháp trị liệu cách tân và hiệu 
quả cao. Những ai làm việc chuyên về sức khỏe tâm thần cần phải xem xét nó nghiêm túc.” – Edith Fiore, TS., bác sỹ tâm lý học lâm sàng và là tác giả cuốn sách Bạn từng ở đây trước 
kia (You Have Been Here Before)', 
'https://salt.tikicdn.com/cache/750x750/ts/product/19/9d/a8/06f79b9ffac98fe9b0f2ae878c
 a7139e.jpg.webp'), 
(24, 3, 6,'Khi Mọi Thứ Sụp Đổ - Lời Khuyên Chân Thành Trong Những Thời Điểm Khó 
Khăn', 1450, 83200, 'Việt Nam', 'Sợ hãi là một trải nghiệm phổ biến. Thậm chí loài côn 
trùng nhỏ nhất cũng biết sợ. Nhúng tay qua làn nước thủy triều, đưa ngón tay lại gần đám 
hải quỳ mở cánh, chúng sẽ lập tức khép lại. Mọi thứ diễn ra một cách tự phát. Sợ hãi khi 
đối diện với những điều chúng ta không biết chẳng phải là điều gì đáng xấu hổ. Nó chỉ là 
một phần của bản năng sinh tồn, tất cả chúng ta đều giống nhau. Chúng ta phản kháng với 
khả năng bị cô đơn, với cái chết, với việc không còn gì để có thể bám vào hay víu lấy. Sợ 
hãi là một phản ứng tự nhiên để tiến gần hơn tới chân lý.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/a4/0c/35/823fe4a9069731cbd032f5434
 1c6f999.jpg.webp'), 
(25, 4, 7,'Nóng Giận Là Bản Năng , Tĩnh Lặng Là Bản Lĩnh', 1640, 57200, 'Việt Nam', 
'Cuốn sách là tập hợp những bài học, lời tâm sự về nhân sinh, luận về cuộc đời của đại sư 
Hoằng Nhất – vị tài tử buông mọi trần tục để quy y cửa Phật, người được mệnh danh tinh 
thông kim cổ và cũng có tầm ảnh hưởng lớn trong Phật giáo.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/45/15/af/39ce2f3f2da7c6f7360ca6f527
 ff07a3.png.webp'), 
(26, 4, 7,'Điều Đẹp Nhất Có Khi Là Buông Tay', 1630, 49000, 'Việt Nam', 'Trong tình yêu, 
chúng ta không thể ép buộc ai đó yêu hay đối xử với mình theo một cách nhất định, luôn 
trung thực, chung thủy, tốt bụng và sẵn sàng giúp đỡ. Nhưng ta có thể yêu bản thân mình 
đủ nhiều để nhận thức được rằng khi nào thì bị đối xử sai trái và xứng đáng nhận được 
những điều tốt đẹp hơn. Vì vậy, nếu một ai đó rời bỏ bạn, hãy để họ đi…', 
'https://salt.tikicdn.com/cache/750x750/ts/product/fa/22/96/e8df06c3e3334bbb9a38e8259
 989d6a5.jpg.webp'), 
(27, 4, 7,'Kỷ Luật Tự Giác ', 1550, 57000, 'Việt Nam', 'Càng tự giác thì càng có nhiều quyền 
lựa chọn. Một ngày, hai ngày, hay thậm chí vài tháng chưa thấy gì, nhưng một năm, hai 
năm, 10 năm, 20 năm sau những người tự giác và những người không tự giác sẽ bước trên 
những con đường hoàn toàn khác nhau. Bởi vì người càng tự giác càng hiểu mình thực sự 
muốn gì, nên mới không cần lãng phí thời gian và sức lực vào những chuyện vô nghĩa.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/27/2e/63/308986aa2c17293af2271628
 74ad24a3.jpg.webp'), 
(28, 4, 7,'Đừng Chỉ Đẹp Mà Không Hiểu Chuyện', 1240, 71200, 'Việt Nam', 'Một con 
người, nhất là người phụ nữ chỉ đẹp mà không hiểu chuyện, vừa là lãng phí của trời cho, 
vừa là thiếu tôn trọng chính mình; vừa dễ bị đàn ông lợi dụng, vừa hay bị những người phụ 
nữ khác coi thường. Chỉ cần sảy tay lỡ miệng thể hiện sự không hiểu chuyện, rất nhiều cô 
gái đã phải trả giá, nhẹ thì vướng vào rắc rối lặt vặt, nặng thì có thể bị lợi dụng, bị hãm 
hại.', 'https://salt.tikicdn.com/cache/750x750/ts/product/b5/83/4e/845cb152cb1f406099524f71
 32639429.jpg.webp'), 
(29, 4, 8,'Mặc Kệ Thiên Hạ - Sống Như Người Nhật', 1360, 74900, 'Việt Nam', 'Mari 
Tamagawa khuyến khích mỗi người nên sống thật và ngưng phán xét bản thân. Thật lãng 
phí khi bạn để cuộc đời mình phải trải qua những tháng ngày khổ sở chỉ vì cái nhìn của 
người khác. Cũng đừng tin vào những “chiếc phao” cứu cánh mà bạn nhầm tưởng rằng sẽ 
giúp mình rũ bỏ được mọi lo lắng. Tổn thương tâm lí, áp lực hay nỗi sợ… của bản thân, 
chúng ta phải đối mặt với nó, chiến đấu và tự chữa trị cho chính mình.', 
'https://salt.tikicdn.com/cache/750x750/media/catalog/product/b/i/bia-1---mac-ke-thien
ha.u5102.d20170323.t155756.324847.jpg.webp'), 
(30, 4, 8,'Chủ Động Trong Thế Giới Bị Động', 1140, 62200, 'Việt Nam', 'Còn trẻ, bạn ném 
mình vào những vòng quay cuộc đời, bạn loay hoay không biết làm sao để cân bằng giữa 
công việc, đam mê và cuộc sống. Điều đó còn tồi tệ hơn khi bạn luôn phải đối mặt với 
những sản phẩm truyền thông ép bạn phải bận rộn, phải làm liên tục không được nghỉ ngơi, 
những mô típ sống tương tự nhau.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/2b/ce/20/be0c1efe1e571377a9f478d9b
 072baf4.jpg.webp'), 
(31, 4, 8,'Luật Tâm Thức - Giải Mã Ma Trận Vũ Trụ', 1270, 316800, 'Việt Nam', 'Sách là 
một kho tàng kiến thức vô tận, tri thức của nhân loại đều được viết và lưu trữ bằng sách. 
Thông qua việc đọc sách, chúng ta có thêm được nhiều điều mới mẻ, những kiến thức thú 
vị trong cuộc sống.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/cf/f2/7d/dae10f9bdd95fec8ab531550bf
 21b2f1.jpg.webp'), 
(32, 4, 8,'Dừng Cuộc Đua Không Phải Là Thua', 1250, 65300, 'Việt Nam', '“Dừng cuộc đua 
không phải là thua”, dừng cuộc đua là cho ta cơ hội nhìn lại những gì mình đi qua, yêu 
thương hiện tại mình đang có và chuẩn bị cho một tương lai rực rỡ tươi đẹp sắp tới.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/1d/b1/bc/1d9b7da5adb1630e1dce28c6
 32e15b8f.jpg.webp'), 
(33, 5, 9,'Thay Đổi Cuộc Sống Với Nhân Số Học ', 1470, 173600, 'Việt Nam', 'Cuốn sách 
“Thay đổi cuộc sống với Nhân số học”mang lại đầy đủ những kiến thức quan trọng nhất 
mà người hứng thú với Nhân số học cần tìm hiểu. Sách bao gồm các kiến thức về ba thể 
trong một con người, con số chủ đạo, biểu đồ ngày sinh, các mũi tên chỉ đặc điểm, con số  
ngày sinh, chu kỳ 9 năm, ba giai đoạn và bốn đỉnh cao của đời người cùng ý nghĩa, sức 
mạnh của cái tên của mỗi người. Các kiến thức này được diễn giải, phân tích và đi kèm các 
ví dụ cụ thể.', 'https://salt.tikicdn.com/cache/750x750/ts/product/15/11/f8/56b303e000cb42faada663569
 fc5d7c9.jpg.webp'), 
(34, 5, 9,'Sách Hiểu Về Trái Tim (Tái Bản 2019) ', 1380, 130500, 'Việt Nam', 'Hiểu Về 
Trái Tim không phải tác phẩm thuyết giáo về Phật pháp. Cuốn sách rất “đời” với những ưu 
tư của một người tu nhìn về cõi thế. Ở đó, có hạnh phúc, có đau khổ, có tình yêu, có cô 
đơn, có tuyệt vọng, có lười biếng, có yếu đuối, có buông xả… Nhưng, tất cả những hỉ nộ 
ái ố ấy đều được khoác lên tấm áo mới, một tấm áo tinh khiết và xuyên suốt, khiến người 
đọc khi nhìn vào, đều thấy mọi sự như nhẹ nhàng hơn…', 
'https://salt.tikicdn.com/cache/750x750/media/catalog/producttmp/1b/d0/54/3f23c300553
 81c7e58af80a62ce28fa5.jpg.webp'), 
(35, 5, 9,'Nghĩ Giàu Và Làm Giàu', 1410, 75200, 'Việt Nam', '"Think and Grow Rich 
Nghĩ giàu và Làm giàu là một trong những cuốn sách bán chạy nhất mọi thời đại. Đã hơn 
60 triệu bản được phát hành với gần trăm ngôn ngữ trên toàn thế giới và được công nhận 
là cuốn sách tạo ra nhiều triệu phú, một cuốn sách truyền cảm hứng thành công nhiều hơn 
bất cứ cuốn sách kinh doanh nào trong lịch sử.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/99/10/67/aa71f851071fc05bec537bec7
 6dc4234.jpg.webp'), 
(36, 5, 9,'Người Giàu Có Nhất Thành Babylon', 1340, 67000, 'Việt Nam', 'Người giàu có 
nhất thành Babylon (tiếng Anh: The Richest Man in Babylon) được xem là một trong 
những tác phẩm truyền cảm hứng lớn nhất về chủ đề tiết kiệm, kế hoạch tài chính và sự 
giàu có cá nhân. Tác phẩm được viết bởi doanh nhân, nhà văn Mỹ George Samuel Clason 
vào năm 1926, kể về cách tiết kiệm, buôn bán và làm giàu của người dân ở thành Babylon 
cổ xưa.', 'https://salt.tikicdn.com/cache/750x750/ts/product/23/f8/75/5e90d6e0eabaebd068c815cf1
 c1f7396.jpg.webp'), 
(37, 5, 10,'OSHO Yêu - Being In Love - Yêu Trong Tỉnh Thức', 1440, 110100, 'Việt Nam', 
'Thông qua từng chương của cuốn sách, bạn đọc nhận diện những dấu hiệu của một tình 
yêu đích thực: Sự cho đi và không chờ đợi được nhận lại, sự trưởng thành cá nhân, đặc biệt 
là sự tỉnh thức khi yêu. “Việc tỉnh táo nhận biết về bản thể của mình là sự khởi đầu của 
hành trình hướng tới tình yêu”.', 
'https://salt.tikicdn.com/cache/750x750/media/catalog/producttmp/2d/e3/d4/fe4142e4c0f
 b202d3d4c01bc9b4ee085.jpg.webp'), 
(38, 5, 10,'Dòng Chảy', 1530, 156000, 'Việt Nam', 'Với 10 chương sách, tác giả Mihaly 
Csikszentmihalyi sẽ từng bước tái cấu trúc hạnh phúc, bằng cách rút ra một công thức bao 
gồm 9 điều kiện cần thiết để đưa mình vào trạng thái dòng chảy. Từ đó giúp bạn có được 
khả năng tập trung cao độ, đạt được hiệu suất tối ưu nhất trong mọi việc cũng như trải 
nghiệm cuộc sống một cách trọn vẹn nhất mà không cần quá nỗ lực hay cố gắng. Bạn sẽ 
sống hạnh phúc hơn, chủ động hơn, và cân bằng hơn trong mọi hoàn cảnh.', 
'https://salt.tikicdn.com/cache/750x750/media/catalog/producttmp/b8/97/4f/b3858b9d285
 701420eaebb6dba56beaf.jpg.webp'), 
(39, 5, 10,'Không Bao Giờ Là Thất Bại - Tất Cả Là Thử Thách', 1470, 173900, 'Việt Nam', 
'Với 9 chương sách, bạn đọc sẽ lần lượt đi qua từng chặng đường mà cố Chủ tịch Chung 
Ju-yung từng trải qua: từ thời thơ ấu thiếu thốn và hành trình thực hiện ước mơ - lên Seoul 
học để đổi đời, cho đến những va vấp khi bắt đầu dấn thân vào thương trường, và cuối cùng 
là chặng đường xây dựng đế chế Hyundai đồ sộ, trở thành bộ mặt của đất nước Hàn Quốc.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/b9/bb/cf/b9c3cb0e86596f31e2bd7ab37
 174a226.jpg.webp'), 
(40, 5, 10,'Người Bán Hàng Vĩ Đại Nhất Thế Giới (Tái Bản 2020)', 1390, 101200, 'Việt 
Nam', 'Người Bán Hàng Vĩ Đại Nhất Thế Giới có một cốt truyện rất độc đáo và thú vị cùng 
văn phong tài tình và cuốn hút. Mỗi người trong chúng ta đều là một nhà kinh doanh, dù ta
thuộc ngành nghề nào. Bởi vì quan trọng nhất là ta phải tiếp thị được bản thân mình cho 
chính mình, chỉ khi đó ta mới tìm được hạnh phúc và sự bình yên trong tâm hồn. Hãy đọc 
thật cẩn thận, tiếp thu và lưu từng chi tiết trong cuốn sáchnày, và nó sẽ giúp bất cứ người 
nào trở thành nhà kinh doanh tài ba nhất.', 
'https://salt.tikicdn.com/cache/750x750/ts/product/35/6e/52/11a1da69fb7597bb62f46205
 7c37b783.jpg.webp'); 
 
INSERT INTO Categories (CategoryID , CategoryName) VALUES 
(1, 'Tiểu thuyết '), 
(2, 'Địa lý '), 
(3, 'Phiêu lưu, tưởng tượng'), 
(4, 'Giáo dục '), 
(5, 'Truyện ngắn'), 
(6, 'Khoa học '), 
(7, 'Trinh thám'), 
(8, 'Tâm lý '), 
(9, 'Kinh dị '), 
(10, 'Văn học hiện đại '), 
(11, 'Lãng mạn '), 
(12, 'Hành động '), 
(13, 'Chính kịch '), 
(14, 'Tuổi mới lớn '), 
(15, 'Tội phạm '), 
(16, 'Kinh tế '), 
(17, 'Self-help '), 
(18, 'Kĩ năng '), 
(19, 'Sức khỏe '), 
(20, 'Trí tuệ '), 
(21, 'Tâm linh '); 

INSERT INTO ProductsCategories (ProductID, CategoryID ) VALUES 
(1, 1), 
(2, 2), 
(3, 3), 
(4, 1), 
(4, 4), 
(4, 14), 
(5, 5), 
(6, 3), 
(6, 12), 
(6, 6), 
(6, 13), 
(7, 7), 
(7, 8), 
(7, 9), 
(8, 8), 
(8, 7), 
(9, 21), 
(9, 6), 
(9, 17), 
(10, 11), 
(10, 12), 
(10, 14), 
(10, 3), 
(10, 15), 
(11, 17), 
(11, 18), 
(12, 17), 
(12, 18), 
(13, 1), 
(14, 17), 
(14, 18), 
(15, 18), 
(15, 17), 
(16, 16), 
(16, 18), 
(16, 20), 
(17, 19), 
(18, 21), 
(18, 18), 
(19, 8), 
(19, 11), 
(20, 17), 
(20, 4), 
(20, 6), 
(21, 8), 
(21, 17), 
(21, 20), 
(22, 8), 
(22, 15), 
(22, 17), 
(23, 3), 
(23, 8), 
(24, 17), 
(24, 8), 
(25, 8), 
(25, 17), 
(26, 11), 
(27, 17), 
(28, 18), 
(28, 20), 
(28, 4), 
(29, 17), 
(30, 17), 
(30, 18), 
(31, 21), 
(32, 17), 
(32, 8), 
(33, 6), 
(33, 20), 
(34, 11), 
(34, 8), 
(35, 17), 
(35, 4), 
(35, 16), 
(36, 16), 
(36, 17), 
(36, 18), 
(37, 11), 
(37, 8), 
(38, 8), 
(39, 1), 
(39, 17), 
(39, 18), 
(40, 16), 
(40, 18), 
(40, 17), 
(40, 3); 

INSERT INTO Orders (OrderID , ConsumerID , FullName, OrderDate, DeliveredDate, 
Status) VALUES 
(1, 1, 'Nguyễn Văn Tài', '2023-01-01', '2023-01-05', 'Delivered'), 
(2, 6, 'Đặng Thị Hằng', '2023-01-02', '2023-01-06', 'Delivered'), 
(3, 2, 'Lê Thị Hoài', '2023-02-02', '2023-02-10', 'Delivered'), 
(4, 4, 'Hoàng Thị Mai', '2023-02-03', '2023-02-11', 'Delivered'), 
(5, 3, 'Trần Văn An', '2023-03-06', '2023-03-18', 'Delivered'), 
(6, 9, 'Nguyễn Thuý Hằng', '2023-03-07', '2023-03-18', 'Delivered'), 
(7, 4, 'Hoàng Thị Mai', '2023-04-07', '2023-04-23', 'Delivered'), 
(8, 7, 'Lê Thị Thuý', '2023-04-08', '2023-04-24', 'Delivered'), 
(9, 5, 'Nguyễn Thanh Bìn', '2023-05-09', '2023-05-12', 'Delivered'), 
(10, 2, 'Lê Thị Hoài', '2023-05-10', '2023-05-13', 'Delivered'), 
(11, 8, 'Lê Hoàng Long', '2023-06-10', '2023-06-15', 'Delivered'), 
(12, 4, 'Hoàng Thị Mai', '2023-06-11', '2023-06-16', 'Delivered'), 
(13, 6, 'Đặng Thị Hằng', '2023-07-12', '2023-07-27', 'Delivered'), 
(14, 8, 'Lê Hoàng Long', '2023-07-13', '2023-07-28', 'Delivered'), 
(15, 7, 'Lê Thị Thuý', '2023-08-13', NULL, 'Cancelled'), 
(16, 4, 'Hoàng Thị Mai', '2023-08-14', '2023-08-29', 'Delivered'), 
(17, 9, 'Nguyễn Thuý Hằng', '2023-08-25', '2023-08-30', 'Delivered'), 
(18, 1, 'Nguyễn Văn Tài', '2023-09-06', '2023-09-10', 'Delivered'), 
(19, 10, 'Lê Minh Quang', '2023-09-18', '2023-09-27', 'Delivered'), 
(20, 2, 'Lê Thị Hoài', '2023-09-30', NULL, 'Cancelled'), 
(21, 8, 'Lê Hoàng Long', '2023-10-12', '2023-10-20', 'Delivered'), 
(22, 4, 'Hoàng Thị Mai', '2023-10-24', '2023-10-30', 'Delivered'), 
(23, 3, 'Trần Văn An', '2023-11-21', '2023-11-29', 'Delivered'), 
(24, 10, 'Lê Minh Quang', '2023-11-22', '2023-11-30', 'Delivered'), 
(25, 6, 'Đặng Thị Hằng', '2023-12-22', '2023-12-28', 'Delivered'), 
(26, 6, 'Đặng Thị Hằng', '2023-12-23', '2023-12-30', 'Delivered'), 
(27, 3, 'Trần Văn An', '2024-01-24', '2024-01-30', 'Delivered'), 
(28, 8, 'Lê Hoàng Long', '2024-01-25', NULL, 'Processing'); 

INSERT INTO OrderDetails (OrderID , ProductID, Quantity, Discount) VALUES 
( 1 ,  5 ,  8 ,  0.15 ) , 
( 2 ,  10 ,  2 ,  0.15 ) , 
( 3 ,  6 ,  10 ,  0.15 ) , 
( 4 ,  7 ,  9 ,  0.00 ) , 
( 5 ,  7 ,  12 ,  0.00 ) , 
( 6 ,  1 ,  8 ,  0.00 ) , 
( 7 ,  6 ,  15 ,  0.12 ) , 
( 8 ,  8 ,  3 ,  0.05 ) , 
( 9 ,  1 ,  2 ,  0.15 ) , 
( 10 ,  6 ,  18 ,  0.2 ) , 
( 11 ,  3 ,  2 ,  0.00 ) , 
( 12 ,  2 ,  3 ,  0.00 ) , 
( 13 ,  3 ,  7 ,  0.05 ) , 
( 15 ,  9 ,  7 ,  0.00 ) , 
( 16 ,  1 ,  6 ,  0.00 ) , 
( 17 ,  2 ,  4 ,  0.12 ) , 
( 18 ,  5 ,  5 ,  0.00 ) , 
( 19 ,  10 ,  5 ,  0.05 ) , 
( 21 ,  7 ,  5 ,  0.00 ) , 
( 22 ,  4 ,  2 ,  0.05 ) , 
( 23 ,  5 ,  4 ,  0.00 ) , 
( 24 ,  5 ,  1 ,  0.12 ) , 
( 25 ,  4 ,  9 ,  0.15 ) , 
( 26 ,  9 ,  9 ,  0.00 ) , 
( 27 ,  7 ,  5 ,  0.05 ) ; 

INSERT INTO Ratings (RatingID , ConsumerID , ProductID, Rating, Review) VALUES 
(1, 1, 1, 5, 'Cây Cam Ngọt Của Tôi là một cuốn sách đầy cảm xúc và sâu sắc về cuộc sống 
và tình yêu. Tác giả đã tạo ra một thế giới đầy màu sắc và những nhân vật đáng yêu, mỗi 
câu chuyện đều chứa đựng một thông điệp sâu sắc về sự kiên nhẫn và hy vọng trong cuộc 
sống'), 
(2, 6, 2, 5, '"Sách Những Tù Nhân của Địa Lý" là một tác phẩm văn học không chỉ tạo ra 
một bức tranh sống động về những tình cảm và trải nghiệm của con người trước bản đồ, 
mà còn mở ra cửa sổ tâm hồn để nhìn nhận về mối quan hệ giữa con người và môi trường 
xung quanh.'), 
(3, 2, 3, 5, '"Những Tù Nhân Của Địa Lý": Một cuốn sách gây sốc và sâu sắc về cuộc chiến 
với bản thân và với thế giới xung quanh. Tác giả đã kỹ lưỡng trong việc phân tích tầm ảnh 
hưởng của môi trường đến tâm hồn con người. Đọc sách này sẽ khiến bạn suy ngẫm về 
mối quan hệ phức tạp giữa con người và môi trường sống.'), 
(4, 4, 4, 4, '"Nhà Giả Kim" (Tái Bản 2020): Một hành trình tìm kiếm ý nghĩa cuộc sống và 
khám phá bản thân đầy cảm động. Cuốn sách này là một lời nhắc nhở về sự quan trọng của 
việc dấn thân vào cuộc hành trình tinh thần để tìm kiếm giá trị thực sự trong cuộc sống.'), 
(5, 3, 5, 4, 'Một câu chuyện đầy cảm xúc về tình yêu và sự hy sinh. Tuy nhiên, một số phần 
của truyện có thể cảm thấy hơi quá mức cảm động'), 
(6, 9, 6, 3, 'Xứ Cát là một cuốn sách gợi mở tâm hồn và mở ra một thế giới đầy bí ẩn và 
sự kỳ diệu của sa mạc. Tác giả đã mô tả sự sống và cảm xúc của nhân vật một cách rất sống 
động, đồng thời truyền tải thông điệp sâu sắc về sự tìm kiếm ý nghĩa trong cuộc sống. Với 
những câu chuyện đan xen giữa hiện thực và giấc mơ, Xứ Cát thực sự là một hành trình 
đáng nhớ qua văn chương.'), 
(7, 4, 7, 2, 'Đây quả thật không phải là cuốn tiểu thuyết thích hợp để bạn đọc thư giãn, hay 
đọc vắn tắt. Bạn cần có thời gian nghiền ngẫm, suy nghĩ về nội dung. '), 
(8, 7, 8, 3, '"Phía Sau Nghi Can X" (Tái Bản 2019): Một câu chuyện ly kỳ và gây căng 
thẳng về việc truy tìm sự thật và công lý. Tác giả đã tạo ra một không khí căng thẳng và bí 
ẩn từ đầu đến cuối, khiến bạn không thể dừng lại trong việc đoán mò và suy luận. Một cuốn 
sách kịch tính và đầy sức hấp dẫn với những bất ngờ đầy kinh ngạc.'), 
(9, 5, 9, 2, '"Như Cơn Gió Thoảng - Nghĩ Về Những Qui Luật Cuộc Sống": Một cuốn sách 
sâu sắc về triết học cuộc sống và sự tồn tại. Tác giả không chỉ đưa ra những quan điểm độc 
đáo mà còn truyền cảm hứng và sự suy ngẫm sâu sắc về những giá trị cốt lõi của cuộc sống. 
Đọc cuốn sách này là một trải nghiệm tâm hồn và tri thức đầy ý nghĩa.'), 
(10, 2, 10, 1, '"Xa Ngoài Kia Nơi Loài Tôm Hát - Where The Crawdads Sing": Một tác 
phẩm văn học đầy cảm xúc và lãng mạn về sự mạnh mẽ của tình yêu và ý chí sống. Tác 
giả đã mô tả một cách tinh tế vẻ đẹp hoang sơ của tự nhiên và con người, đồng thời kể một 
câu chuyện đầy cảm động về sự đấu tranh và tự do. Cuốn sách này là một điểm sáng trong 
văn học hiện đại và xứng đáng được đọc.'), 
(11, 8, 11, 1, 'Xa Ngoài Kia Nơi Loài Tôm Hát - Where The Crawdads Sing: Cuốn sách 
này mang đến một câu chuyện đầy cảm xúc về sự cô đơn, tình yêu và sự đấu tranh cho sự 
tự do. Với môi trường thiên nhiên phong phú và nhân vật sâu sắc, đây là một cuốn sách 
đáng đọc.'), 
(12, 4, 12, 4, '"Từ Tốt Đến Vĩ Đại" (Tái bản 2021): Cuốn sách này là một hướng dẫn chi 
tiết và cụ thể về việc phát triển bản thân và doanh nghiệp từ tốt đến vĩ đại. Tác giả đã trình 
bày những nguyên tắc cơ bản và chiến lược kinh doanh một cách rõ ràng và minh bạch, 
cung cấp những bài học quý giá từ các công ty thành công nhất thế giới.'), 
(13, 6, 13, 5, '"Suối Nguồn" (Tái Bản): Một tác phẩm văn học tinh tế và sâu sắc về tình 
yêu, sự hy sinh và bí mật của quá khứ. Tác giả đã tạo ra một thế giới với những nhân vật 
sống động và câu chuyện đầy cảm xúc, làm cho người đọc không thể rời mắt khỏi trang 
sách.'), 
(14, 8, 15, 3, '"Ngày Xưa Có Một Con Bò…" (Tái Bản): Một câu chuyện dành cho mọi 
lứa tuổi về sự hồn nhiên và đẹp đẽ của tuổi thơ. Tác giả đã thổi vào cuộc sống của nhân vật 
chính một luồng gió mới, mang lại niềm vui và ý nghĩa cho cuộc sống hàng ngày. Cuốn 
sách này là một điều tuyệt vời để đọc và thưởng thức cùng gia đình và bạn bè.'), 
(15, 7, 16, 3, 'Nhà Lãnh Đạo Không Chức Danh: Cuốn sách này là một hướng dẫn chi tiết 
về cách thúc đẩy lãnh đạo trong mọi khía cạnh của cuộc sống, không cần phải có một vị trí 
chức danh cụ thể. Nó làm nổi bật vai trò của sự lãnh đạo trong mỗi cá nhân.'), 
(16, 4, 17, 4, '"Cơ Thể Ta Đã Hai Triệu Năm - Giải Mã Các Căn Bệnh Thời Hiện Đại": 
Một cuốn sách thú vị và chi tiết về nguồn gốc và cách phòng tránh các căn bệnh hiện đại. 
Tác giả đã kết hợp kiến thức khoa học và lịch sử để giúp độc giả hiểu rõ hơn về cơ thể và 
làm thế nào để giữ gìn sức khỏe.'), 
(17, 9, 18, 5, '"Power Vs Force - Trường Năng Lượng Và Những Nhân Tố Quyết Định 
Hành Vi Của Con Người" (Tái Bản): Một cuốn sách sâu sắc về năng lượng và tinh thần 
con người. Tác giả khám phá sự tương tác giữa quyền lực và sức mạnh, giúp độc giả hiểu 
rõ hơn về nguồn gốc của hành vi và cách chúng ta tương tác với nhau.'), 
(18, 1, 19, 5, '"Kiếp Nào Ta Cũng Tìm Thấy Nhau: Câu Chuyện Về Những Linh Hồn Tri 
Kỷ Vĩnh Viễn Không Chia Lìa" (Tái Bản): Một câu chuyện đầy cảm xúc về tình bạn và sự 
kết nối vĩnh cửu. Tác giả đã tạo ra một bức tranh rộng lớn về tình bạn và sự đồng điệu của 
những linh hồn gặp nhau qua nhiều kiếp.'), 
(19, 10, 21, 2, '"Sự Trung Thực Của Xác Chết – Ghi Chép Của Một Nhà Pháp Y": Một 
cuốn sách gây sốc và sâu sắc về sự trung thực và cái chết. Tác giả chia sẻ những câu chuyện 
và ghi chép từ những trải nghiệm của mình, giúp độc giả suy ngẫm về ý nghĩa và giá trị 
của cuộc sống.'), 
(20, 2, 22, 2, '"Chiến Thắng Con Quỷ Trong Bạn - Bí Quyết Tự Do Và Thành Công" (Tái 
Bản): Một hướng dẫn cụ thể và thực tiễn về cách vượt qua các thử thách trong cuộc sống. 
Tác giả truyền đạt những bí quyết và chiến lược để đạt được tự do và thành công trong mọi 
lĩnh vực của cuộc sống.'), 
(21, 8, 23, 1, '"Bàn Về Ham Muốn: Tại Sao Chúng Ta Muốn Thứ Mà Ta Muốn": Một cuốn 
sách triết học về bản chất của ham muốn và ý nghĩa của nó trong cuộc sống. Tác giả phân 
tích cặn kẽ về nguồn gốc và tác động của ham muốn đến hành vi và trải nghiệm của con 
người.'), 
(22, 4, 24, 3, '"Ám Ảnh Từ Kiếp Trước - Bí Mật Của Sự Sống Và Cái Chết" (Tái Bản 
2020): Một cuốn sách mở ra cánh cửa vào thế giới tâm linh và huyền bí của kiếp trước và 
kiếp sau. Tác giả chia sẻ những câu chuyện và phân tích về sự sống và cái chết, giúp độc 
giả hiểu sâu hơn về ý nghĩa của cuộc sống và sự tồn tại.'), 
(23, 3, 25, 1, '"Khi Mọi Thứ Sụp Đổ - Lời Khuyên Chân Thành Trong Những Thời Điểm 
Khó Khăn": Một cuốn sách truyền cảm hứng và động viên trong những thời điểm khó khăn. 
Tác giả chia sẻ những lời khuyên chân thành và kiến thức sâu sắc để giúp độc giả vượt qua 
những khó khăn trong cuộc sống.'), 
(24, 10, 26, 2, '"Nóng Giận Là Bản Năng, Tĩnh Lặng Là Bản Lĩnh": Một cuốn sách tự 
truyện và tâm lý học về quá trình kiểm soát cảm xúc và phản ứng của con người. Tác giả 
chia sẻ những trải nghiệm và bài học từ cuộc sống để giúp độc giả hiểu rõ hơn về bản chất 
của nóng giận và tĩnh lặng.'), 
(25, 6, 27, 4, '"Điều Đẹp Nhất Có Khi Là Buông Tay": Một cuốn sách truyền cảm hứng 
về sự thả lỏng và giải phóng bản thân. Tác giả khuyến khích độc giả nắm bắt cơ hội và đối 
diện với thách thức của cuộc sống một cách tự tin và bình tĩnh.'); 
