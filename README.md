
Claw Quest Bot - 1.0

HDSD:
- data.txt : định dạng query/user_id
- proxy.txt: định dạng ip:port:user:pass
- wallet.txt: 24 cụm từ bí mật ví ton/ mỗi ví 1 dòng
+ lưu ý: nên chạy 1 lượt connect ví xong thì tắt chức năng này đi
- Cấu hình file config:
"skip_tutorial_enabled": true,  (bật cho acc mới => acc cũ qua tân thủ rồi thì tắt đi)  
"openclaw_mining_enabled": true,   (luôn bật) 
"openclaw_auto_buy_stamina": true, (luôn bật)   
"openclaw_stamina_buy_limit": 2000, (set limit dùng kim cương mua năng lượng)    
"skilltree_enabled": true,  (nâng cấp skill tree)  
"pickaxe_enabled": true,   (trang bị búa lv cao nhất)
"lucky_spin_enabled": true,  (lucky spin - mỗi ngày được spin 1 lần)  
"task_enabled": true,  (làm tasl - all)  
"threads": 10,    (số luồng chạy)
"repeat_interval": 300,    (time lặp lại)
"connect_wallet_enabled": false (set bật/tắt connect ví)
