添加BE6500PRO dts   bdf 文件

	qcom,ipq5332-ap-mi01.2)
		ucidef_set_interfaces_lan_wan "eth1" "eth0"
		ucidef_add_switch "switch1" \
		"1:lan" "2:lan" "3:lan" "0u@eth1" "4:wan" "5u@eth0"
	;;
