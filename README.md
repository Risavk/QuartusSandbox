# QuartusSandbox
Placeholder for quartus/fpga stuff... 
Maybe in near future Yet Another VHDL Editor with Quartus toolchain for MAX10 (and maybe for Cyclone II - for old Altera DE2) ... Will see.

As for now only something which should be publicly available - but is not .... Don't know why.

You know those nice RTL and Technology views available inside Quartus ? 
Of course - we can execute qnui.exe in Bin64 dir of Quartus - and get RTL View without problems.

But what about technology one ? ;) 

```qnui.exe --type=tech_map TopEntity.qp```  

And voila. And Bob is your uncle ;]

Full list is:
* **qnui.exe --type=nui TopEntity.qpf**  
* **qnui.exe --type=tech_map TopEntity.qpf**  
* **qnui.exe --type=tech_fit TopEntity.qpf**  
* **qnui.exe --type=schematic TopEntity.qpf**  
* **qnui.exe --type=snapshot TopEntity.qpf**  

Shame there is no way to export to pdf directly without executing app - but can't have it all.
