# RAM 8x8 SystemVerilog Verification

Project thiết kế và kiểm chứng RAM gồm 8 ô nhớ, mỗi ô chứa 8 bit.

## Chức năng

- Ghi dữ liệu vào RAM.
- Đọc dữ liệu từ RAM.
- Reset ngõ ra.
- Kiểm tra bằng directed test và random test.
- Sử dụng scoreboard, assertion và functional coverage.

## Files

- `design.sv`: Thiết kế RAM 8x8.
- `testbench.sv`: Môi trường kiểm chứng SystemVerilog.

## Công cụ

- Cadence Xcelium 25.03
- EDA Playground
- EPWave

## run

1. Chọn SystemVerilog/Verilog.
2. Chọn Cadence Xcelium.
3. Dán thiết kế vào `ram8x8design.sv`.
4. Dán testbench vào `tb8x8.sv`.
5.  Run.


```text
FINAL RESULT        : TEST PASSED
Total errors        : 0
