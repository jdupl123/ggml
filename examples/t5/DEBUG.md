building model currently segfaults

./build/bin/t5 /data/ggml-models/t5/small/ggml-t5-model.bin 
t5_model_load: loading model from '/data/ggml-models/t5/small/ggml-t5-model.bin'
t5_model_load: n_vocab       = 32128
t5_model_load: d_ff          = 1024
t5_model_load: d_kv          = 64
t5_model_load: d_model       = 512
t5_model_load: n_positions   = 512
t5_model_load: n_head        = 6
t5_model_load: n_layer       = 8
t5_model_load: f16           = 1
t5_model_load: type          = 1
t5_model_load: adding 28 extra tokens
t5_model_load: mem_required  = 1560.00 MB
t5_model_load: ggml ctx size =  209.63 MB
[1]    101349 segmentation fault (core dumped)  ./build/bin/t5 /data/ggml-models/t5/small/ggml-t5-model.bin
