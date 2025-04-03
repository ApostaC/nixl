# Run the benchmark

Open terminal 1:
```bash
python3 benchmark.py --role creator --operation READ --device cpu
```

Open terminal 2:
```bash
python3 benchmark.py --role peer --operation READ --device cpu
```

# Available options
```plaintext
--operation: READ | WRITE 
--device: cpu | cuda | cuda:<device_id>
--num-blocks: <int>, default 100
--num-layers: <int>, default 32
--block-size: <int>, default 256
--hidden-size: <int>, default 1024
--dtype: bfloat16 
```
