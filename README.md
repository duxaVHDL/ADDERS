# ADDERS
HALF BIT ADDER
module Main(S, C, X, Y);
  output S,  C;
  input X, Y;
  wire xor_0_out, and_0_out;
  assign xor_0_out = X ^ Y;
  assign S = xor_0_out;
  assign and_0_out = X & Y;
  assign C = and_0_out;
endmodule
