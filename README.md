# Spherical-Cautious-Optimizers

'./distributed_train.sh 2   /home/liujiachen/code/CR/data/mini_imagenet_folders/   --num-classes 100   --model vit_wee_patch16_reg1_gap_256   -j 8 --epochs 200 --warmup-prefix --sched-on-updates --warmup-lr 0   --mixup .2 --model-ema --model-ema-decay 0.999 --model-ema-warmup   --aa rand-m9-mstd0.5-inc1 --remode pixel --reprob 0.25 --amp   --weight-decay .05 --drop 0.1 --drop-path .1 -b 288   --opt cadamp --lr 1e-3 --seed 42 '
