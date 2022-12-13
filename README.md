Khởi tạo VLAN
Switch(config)# vlan vlan-id
Switch(config-vlan)# name Tên_VLAN

Gán cổng vào VLAN
Switch(config)# interface range f0/1 - 16
Switch(config-if)# switchport access vlan vlan-id

Hiện kết quả
Switch# show vlan
