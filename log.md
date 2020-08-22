*2020.08.22.128*:

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm/model_best.pth, epoch 205
	3.4791402220726013 ms,  287.42733439018383 fps,
        	     precision    recall  f1-score   support

 	carringbag       0.89      0.99      0.93       400
 	  umbrella       0.97      1.00      0.99       400
	  
	avg / total       0.93      0.99      0.96       800
	
*2020.08.22.384*：

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_last.pth, epoch 400
	11.020184755325317 ms,  90.74258029265499 fps,
	             precision    recall  f1-score   support

	 carringbag       0.97      0.80      0.88       400
	   umbrella       0.86      0.95      0.91       400

	avg / total       0.91      0.88      0.89       800
	
*2020.08.20*:

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140
	9.453112557530403 ms,  105.78526320448753 fps,
	             precision    recall  f1-score   support
	
	 carringbag       0.95      0.83      0.89       400
	   umbrella       0.88      0.96      0.92       400
	
	avg / total       0.91      0.89      0.90       800

Conclusion:
1. mobilenetv2_10 get lower precison use inputsize 384. (0.95 && 0.98, mAP=0.965 mobilenetv2simUptrunc_0)
2. 
	1. onnx (cpu test) precision deviation, error.
	2. cpu test speed is useless:

	==> 158.32575857639313 ms,  6.316091639109336 fps,
	['carringbag', 'umbrella']
	------[Class] Miss Rate, Average Precision and Average Groundtruth Scores------
	[class carringbag] AP=0.16, MR (1 FPPI)=0.68
	[class umbrella] AP=0.03, MR (1 FPPI)=0.81
	------[Average Per Class] Miss Rate, Average Precision and Average Groundtruth Scores------
	MR (1 FPPI) per class=0.75
	AP per class=0.09
	             precision    recall  f1-score   support
	
	 carringbag       0.67      0.66      0.66       400
	   umbrella       0.52      0.75      0.62       400
	
	avg / total       0.60      0.70      0.64       800

