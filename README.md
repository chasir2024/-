baseline+ 用户态V1 吞吐量对比

  指标             	基准测试 (直通)       	引入 NFQUEUE 程序后	变化        
  发送端平均带宽        	4.70 Gbits/sec  	312 Mbits/sec 	下降了约 93.3%
  TCP 拥塞窗口 (Cwnd)	最高达到 2.23 MBytes	卡死在 363 KBytes	缩小了近 6 倍  
  重传次数 (Retr)    	7 次 (极少)        	0 次           	没有丢包，纯粹是慢 


