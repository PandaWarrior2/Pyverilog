```SystemVerilog
always @(negedge clk) begin
  assert (!(wr_en && rd_en))
  else begin
    $display("error!");
  end
end
```
эквивалентно выражению
```verilog
always @(negedge clk) begin
  if (!(wr_en && rd_en))
  else begin
    $display("error!");
  end
end
```
