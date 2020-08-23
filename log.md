
*2020.08.22.256_2ft*:

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_256_2ft/model_last.pth, epoch 400
	5.943152904510498 ms,  168.26085683258455 fps,
         	    precision    recall  f1-score   support

 	carringbag       0.90      0.91      0.90       400
 	  umbrella       0.90      0.99      0.94       400

	avg / total       0.90      0.95      0.92       800
*2020.08.22.384_2rsltn*:

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384_2rsltn/model_best.pth, epoch 150
	9.530677914619446 ms,  104.92433056268374 fps,
	             precision    recall  f1-score   support

 	carringbag       0.96      0.85      0.90       400
 	  umbrella       0.88      0.97      0.92       400

	avg / total       0.92      0.91      0.91       800



	3.9398851990699764 ms,  253.8145020662159 fps,
  	           precision    recall  f1-score   support

	 carringbag       0.90      0.38      0.54       400
 	   umbrella       0.94      0.94      0.94       400

	avg / total       0.92      0.66      0.74       800



*2020.08.22.256*:

	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_256/model_best.pth, epoch 155
	5.430400311946869 ms,  184.1484867699352 fps,
          	   precision    recall  f1-score   support
	
 	carringbag       0.91      0.91      0.91       400
 	  umbrella       0.89      0.99      0.94       400

	avg / total       0.90      0.95      0.92       800
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

	08.20: 384*128
	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140
	9.453112557530403 ms,  105.78526320448753 fps,
	             precision    recall  f1-score   support
	
	 carringbag       0.95      0.83      0.89       400
	   umbrella       0.88      0.96      0.92       400
	
	avg / total       0.91      0.89      0.90       800
	
	0822: 384*384
	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140

	9.899441167712212 ms,  101.01580312044045 fps,
        	     precision    recall  f1-score   support

 	carringbag       0.95      0.83      0.89       400
	   umbrella       0.88      0.96      0.92       400

	avg / total       0.91      0.89      0.90       800
	
	0822:128*128
	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140
	3.846625655889511 ms,  259.96810957388453 fps,
       	      precision    recall  f1-score   support
	
	 carringbag       0.90      0.35      0.50       400
 	  umbrella       0.92      0.87      0.89       400

	avg / total       0.91      0.61      0.70       800
	
	0822:carrybagum:384, opt:128
	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140
	9.406557440757751 ms,  106.30881768361841 fps,
  	           precision    recall  f1-score   support

 	carringbag       0.95      0.83      0.89       400
	   umbrella       0.88      0.96      0.92       400

	avg / total       0.91      0.89      0.90       800

	
	0822: 384*384
	==> initializing Carring bag & Umbrella warp data (1 subsets).
	#images: 800 (carringbag 400) (umbrella 400)
	loaded ../exp/ctdet/multidet_carryBagUm_384/model_best.pth, epoch 140
	13.671024143695831 ms,  73.14740940320361 fps,
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

