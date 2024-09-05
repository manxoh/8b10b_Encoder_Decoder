http://asics.chuckbenz.com/#My_open_source_8b10b_encoderdecoder

Instructions for Questa

rm -rf work

vlib work

vlog encode.v decode.v validate_8b10b.v

vsim -voptargs="+acc" test_8b10b -do "run -all"
