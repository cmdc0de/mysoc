
romtb:
	iverilog -g2005-sv -Irtl -o out/romtb.out sim/romtb.v
	vvp out/romtb.out

memtb:
	iverilog -g2005-sv -Irtl -o out/memtb.out sim/memtb.v
	vvp out/memtb.out

regtb:
	iverilog -Irtl -o out/regtb.out sim/register_tb.v
	vvp out/regtb.out


