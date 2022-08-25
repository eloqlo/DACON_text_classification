## ERROR 1 : Loss[1.94591], Acc[1.105499],[1.105548] for "fold1,4"
- Train Loss, Valid Loss 값이 똑같게 나온다.
- Accuracy 는 다르지만, 거의 비슷한 수준이다.

1. 아예 같은 Loss 가 나온다는 것 은, 같은 데이터가 들어갔다는 것 이고,
2. 다른 데이터셋인데 Train, Valid Loss가 같다는것은, --> 
    - 구글링해보니, weight 들이 .eval() 모드에서 잘 loaded 됐는지 확인하라 한다.
3. 한 데이터셋에서 (Valid)Acc가 같다는 것은, --> epoch마다 train data를 통해 학습이 전혀 이뤄지지 않았다는 것 이다.

<br/><br/><br/><br/>


Fold 0 Processing ...
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.15it/s]
Epoch 1  |  Train Loss : [1.65271]  |  Train Acc: [0.350487] 
Epoch 1  |  Valid Loss : [1.16589]  |  Valid Acc: [0.582577] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.03it/s]
Epoch 2  |  Train Loss : [1.01163]  |  Train Acc: [0.646704] 
Epoch 2  |  Valid Loss : [0.87143]  |  Valid Acc: [0.705765] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.79it/s]
Epoch 3  |  Train Loss : [0.79076]  |  Train Acc: [0.729700] 
Epoch 3  |  Valid Loss : [0.79209]  |  Valid Acc: [0.737287] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.86it/s]
Epoch 4  |  Train Loss : [0.65250]  |  Train Acc: [0.778776] 
Epoch 4  |  Valid Loss : [0.72909]  |  Valid Acc: [0.752201] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.97it/s]
Epoch 5  |  Train Loss : [0.55868]  |  Train Acc: [0.811490] 
Epoch 5  |  Valid Loss : [0.67885]  |  Valid Acc: [0.774600] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.72it/s]
Epoch 6  |  Train Loss : [0.47889]  |  Train Acc: [0.837909] 
Epoch 6  |  Valid Loss : [0.62859]  |  Valid Acc: [0.794049] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.14it/s]
Epoch 7  |  Train Loss : [0.42099]  |  Train Acc: [0.858214] 
Epoch 7  |  Valid Loss : [0.64945]  |  Valid Acc: [0.794593] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.16it/s]
Epoch 8  |  Train Loss : [0.36758]  |  Train Acc: [0.875180] 
Epoch 8  |  Valid Loss : [0.62149]  |  Valid Acc: [0.804371] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.06it/s]
Epoch 9  |  Train Loss : [0.32066]  |  Train Acc: [0.890353] 
Epoch 9  |  Valid Loss : [0.63705]  |  Valid Acc: [0.810434] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.08it/s]
Epoch 10  |  Train Loss : [0.28206]  |  Train Acc: [0.904377] 
Epoch 10  |  Valid Loss : [0.64048]  |  Valid Acc: [0.812566] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.89it/s]
Epoch 11  |  Train Loss : [0.24994]  |  Train Acc: [0.915172] 
Epoch 11  |  Valid Loss : [0.63676]  |  Valid Acc: [0.816334] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 34.15it/s]
Epoch 12  |  Train Loss : [0.22043]  |  Train Acc: [0.926049] 
Epoch 12  |  Valid Loss : [0.64209]  |  Valid Acc: [0.816279] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 34.16it/s]
Epoch 13  |  Train Loss : [0.19542]  |  Train Acc: [0.933369] 
Epoch 13  |  Valid Loss : [0.66828]  |  Valid Acc: [0.818136] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.07it/s]
Epoch 14  |  Train Loss : [0.17000]  |  Train Acc: [0.943261] 
Epoch 14  |  Valid Loss : [0.68017]  |  Valid Acc: [0.822835] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.98it/s]
Epoch 15  |  Train Loss : [0.15128]  |  Train Acc: [0.948747] 
Epoch 15  |  Valid Loss : [0.73998]  |  Valid Acc: [0.815953] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.10it/s]
Epoch 16  |  Train Loss : [0.13355]  |  Train Acc: [0.956696] 
Epoch 16  |  Valid Loss : [0.73336]  |  Valid Acc: [0.817153] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.09it/s]
Epoch 17  |  Train Loss : [0.11952]  |  Train Acc: [0.960843] 
Epoch 17  |  Valid Loss : [0.75487]  |  Valid Acc: [0.820596] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.08it/s]
Epoch 18  |  Train Loss : [0.11084]  |  Train Acc: [0.962498] 
Epoch 18  |  Valid Loss : [0.75472]  |  Valid Acc: [0.822288] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.20it/s]
Epoch 19  |  Train Loss : [0.09843]  |  Train Acc: [0.968313] 
Epoch 19  |  Valid Loss : [0.79561]  |  Valid Acc: [0.812510] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.12it/s]
Epoch 20  |  Train Loss : [0.08697]  |  Train Acc: [0.972158] 
Epoch 20  |  Valid Loss : [0.80255]  |  Valid Acc: [0.819175] 
================ model saved ================
Fold 1 Processing ...
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.10it/s]
Epoch 1  |  Train Loss : [1.94586]  |  Train Acc: [0.108004] 
Epoch 1  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.94it/s]
Epoch 2  |  Train Loss : [1.94591]  |  Train Acc: [0.105652] 
Epoch 2  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.78it/s]
Epoch 3  |  Train Loss : [1.94591]  |  Train Acc: [0.105639] 
Epoch 3  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.95it/s]
Epoch 4  |  Train Loss : [1.94591]  |  Train Acc: [0.105639] 
Epoch 4  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.82it/s]
Epoch 5  |  Train Loss : [1.94591]  |  Train Acc: [0.105719] 
Epoch 5  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.98it/s]
Epoch 6  |  Train Loss : [1.94591]  |  Train Acc: [0.105666] 
Epoch 6  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.90it/s]
Epoch 7  |  Train Loss : [1.94591]  |  Train Acc: [0.105719] 
Epoch 7  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.01it/s]
Epoch 8  |  Train Loss : [1.94591]  |  Train Acc: [0.105625] 
Epoch 8  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.02it/s]
Epoch 9  |  Train Loss : [1.94591]  |  Train Acc: [0.105679] 
Epoch 9  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.00it/s]
Epoch 10  |  Train Loss : [1.94591]  |  Train Acc: [0.105679] 
Epoch 10  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.85it/s]
Epoch 11  |  Train Loss : [1.94591]  |  Train Acc: [0.105706] 
Epoch 11  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.99it/s]
Epoch 12  |  Train Loss : [1.94591]  |  Train Acc: [0.105706] 
Epoch 12  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.93it/s]
Epoch 13  |  Train Loss : [1.94591]  |  Train Acc: [0.105692] 
Epoch 13  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.94it/s]
Epoch 14  |  Train Loss : [1.94591]  |  Train Acc: [0.105706] 
Epoch 14  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.85it/s]
Epoch 15  |  Train Loss : [1.94591]  |  Train Acc: [0.105666] 
Epoch 15  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.96it/s]
Epoch 16  |  Train Loss : [1.94591]  |  Train Acc: [0.105706] 
Epoch 16  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.93it/s]
Epoch 17  |  Train Loss : [1.94591]  |  Train Acc: [0.105625] 
Epoch 17  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.05it/s]
Epoch 18  |  Train Loss : [1.94591]  |  Train Acc: [0.105652] 
Epoch 18  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.04it/s]
Epoch 19  |  Train Loss : [1.94591]  |  Train Acc: [0.105679] 
Epoch 19  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.98it/s]
Epoch 20  |  Train Loss : [1.94591]  |  Train Acc: [0.105666] 
Epoch 20  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105548] 
================ model saved ================
Fold 2 Processing ...
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.03it/s]
Epoch 1  |  Train Loss : [1.74177]  |  Train Acc: [0.298006] 
Epoch 1  |  Valid Loss : [1.48775]  |  Valid Acc: [0.443372] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.88it/s]
Epoch 2  |  Train Loss : [1.34537]  |  Train Acc: [0.505328] 
Epoch 2  |  Valid Loss : [1.12533]  |  Valid Acc: [0.591201] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.12it/s]
Epoch 3  |  Train Loss : [1.07331]  |  Train Acc: [0.609175] 
Epoch 3  |  Valid Loss : [1.04745]  |  Valid Acc: [0.610539] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.03it/s]
Epoch 4  |  Train Loss : [0.85736]  |  Train Acc: [0.694165] 
Epoch 4  |  Valid Loss : [0.73121]  |  Valid Acc: [0.754274] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.03it/s]
Epoch 5  |  Train Loss : [0.60607]  |  Train Acc: [0.798822] 
Epoch 5  |  Valid Loss : [0.73046]  |  Valid Acc: [0.761867] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.02it/s]
Epoch 6  |  Train Loss : [0.50644]  |  Train Acc: [0.834559] 
Epoch 6  |  Valid Loss : [0.65043]  |  Valid Acc: [0.786500] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.09it/s]
Epoch 7  |  Train Loss : [0.43962]  |  Train Acc: [0.855506] 
Epoch 7  |  Valid Loss : [0.62015]  |  Valid Acc: [0.800707] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.98it/s]
Epoch 8  |  Train Loss : [0.38888]  |  Train Acc: [0.869392] 
Epoch 8  |  Valid Loss : [0.61669]  |  Valid Acc: [0.810269] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.08it/s]
Epoch 9  |  Train Loss : [0.33505]  |  Train Acc: [0.888055] 
Epoch 9  |  Valid Loss : [0.60736]  |  Valid Acc: [0.813654] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.91it/s]
Epoch 10  |  Train Loss : [0.29807]  |  Train Acc: [0.899479] 
Epoch 10  |  Valid Loss : [0.63009]  |  Valid Acc: [0.812345] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.94it/s]
Epoch 11  |  Train Loss : [0.25958]  |  Train Acc: [0.914324] 
Epoch 11  |  Valid Loss : [0.63226]  |  Valid Acc: [0.818627] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.92it/s]
Epoch 12  |  Train Loss : [0.22796]  |  Train Acc: [0.923519] 
Epoch 12  |  Valid Loss : [0.62697]  |  Valid Acc: [0.820428] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.15it/s]
Epoch 13  |  Train Loss : [0.20587]  |  Train Acc: [0.931180] 
Epoch 13  |  Valid Loss : [0.64771]  |  Valid Acc: [0.822120] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.12it/s]
Epoch 14  |  Train Loss : [0.17949]  |  Train Acc: [0.939567] 
Epoch 14  |  Valid Loss : [0.73426]  |  Valid Acc: [0.815239] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.10it/s]
Epoch 15  |  Train Loss : [0.15745]  |  Train Acc: [0.947324] 
Epoch 15  |  Valid Loss : [0.71708]  |  Valid Acc: [0.817094] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.15it/s]
Epoch 16  |  Train Loss : [0.14226]  |  Train Acc: [0.953140] 
Epoch 16  |  Valid Loss : [0.73833]  |  Valid Acc: [0.819010] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.13it/s]
Epoch 17  |  Train Loss : [0.12529]  |  Train Acc: [0.959145] 
Epoch 17  |  Valid Loss : [0.74512]  |  Valid Acc: [0.816329] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.91it/s]
Epoch 18  |  Train Loss : [0.11167]  |  Train Acc: [0.963770] 
Epoch 18  |  Valid Loss : [0.76298]  |  Valid Acc: [0.818898] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.81it/s]
Epoch 19  |  Train Loss : [0.10234]  |  Train Acc: [0.966315] 
Epoch 19  |  Valid Loss : [0.77472]  |  Valid Acc: [0.822014] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.77it/s]
Epoch 20  |  Train Loss : [0.08979]  |  Train Acc: [0.970529] 
Epoch 20  |  Valid Loss : [0.82964]  |  Valid Acc: [0.817862] 
================ model saved ================
Fold 3 Processing ...
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.52it/s]
Epoch 1  |  Train Loss : [1.48921]  |  Train Acc: [0.438353] 
Epoch 1  |  Valid Loss : [1.07765]  |  Valid Acc: [0.608857] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.44it/s]
Epoch 2  |  Train Loss : [0.96942]  |  Train Acc: [0.663615] 
Epoch 2  |  Valid Loss : [0.88814]  |  Valid Acc: [0.697845] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.79it/s]
Epoch 3  |  Train Loss : [0.77816]  |  Train Acc: [0.735858] 
Epoch 3  |  Valid Loss : [0.73619]  |  Valid Acc: [0.750015] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 34.19it/s]
Epoch 4  |  Train Loss : [0.65239]  |  Train Acc: [0.779693] 
Epoch 4  |  Valid Loss : [0.66446]  |  Valid Acc: [0.780660] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.46it/s]
Epoch 5  |  Train Loss : [0.54998]  |  Train Acc: [0.815403] 
Epoch 5  |  Valid Loss : [0.64391]  |  Valid Acc: [0.788695] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 32.24it/s]
Epoch 6  |  Train Loss : [0.47638]  |  Train Acc: [0.837145] 
Epoch 6  |  Valid Loss : [0.60827]  |  Valid Acc: [0.804915] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.54it/s]
Epoch 7  |  Train Loss : [0.41511]  |  Train Acc: [0.860690] 
Epoch 7  |  Valid Loss : [0.58676]  |  Valid Acc: [0.811689] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.41it/s]
Epoch 8  |  Train Loss : [0.37243]  |  Train Acc: [0.873634] 
Epoch 8  |  Valid Loss : [0.60200]  |  Valid Acc: [0.815130] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 32.80it/s]
Epoch 9  |  Train Loss : [0.32579]  |  Train Acc: [0.889737] 
Epoch 9  |  Valid Loss : [0.58695]  |  Valid Acc: [0.818845] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.05it/s]
Epoch 10  |  Train Loss : [0.29004]  |  Train Acc: [0.902092] 
Epoch 10  |  Valid Loss : [0.63319]  |  Valid Acc: [0.810599] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.52it/s]
Epoch 11  |  Train Loss : [0.25893]  |  Train Acc: [0.913502] 
Epoch 11  |  Valid Loss : [0.61276]  |  Valid Acc: [0.817592] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:17<00:00, 33.01it/s]
Epoch 12  |  Train Loss : [0.22889]  |  Train Acc: [0.923203] 
Epoch 12  |  Valid Loss : [0.60150]  |  Valid Acc: [0.823437] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.79it/s]
Epoch 13  |  Train Loss : [0.19960]  |  Train Acc: [0.932042] 
Epoch 13  |  Valid Loss : [0.63560]  |  Valid Acc: [0.822669] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.54it/s]
Epoch 14  |  Train Loss : [0.18123]  |  Train Acc: [0.938432] 
Epoch 14  |  Valid Loss : [0.66504]  |  Valid Acc: [0.823927] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.83it/s]
Epoch 15  |  Train Loss : [0.15813]  |  Train Acc: [0.945655] 
Epoch 15  |  Valid Loss : [0.70766]  |  Valid Acc: [0.817702] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 36.08it/s]
Epoch 16  |  Train Loss : [0.13660]  |  Train Acc: [0.953933] 
Epoch 16  |  Valid Loss : [0.70028]  |  Valid Acc: [0.824092] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.95it/s]
Epoch 17  |  Train Loss : [0.12083]  |  Train Acc: [0.960336] 
Epoch 17  |  Valid Loss : [0.70263]  |  Valid Acc: [0.828626] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.75it/s]
Epoch 18  |  Train Loss : [0.11054]  |  Train Acc: [0.963907] 
Epoch 18  |  Valid Loss : [0.78752]  |  Valid Acc: [0.815620] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.91it/s]
Epoch 19  |  Train Loss : [0.10213]  |  Train Acc: [0.966672] 
Epoch 19  |  Valid Loss : [0.74199]  |  Valid Acc: [0.824308] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.94it/s]
Epoch 20  |  Train Loss : [0.08715]  |  Train Acc: [0.971419] 
Epoch 20  |  Valid Loss : [0.79089]  |  Valid Acc: [0.820431] 
================ model saved ================
Fold 4 Processing ...
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.81it/s]
Epoch 1  |  Train Loss : [1.94607]  |  Train Acc: [0.107561] 
Epoch 1  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
============= Best model saved! =============
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.72it/s]
Epoch 2  |  Train Loss : [1.94591]  |  Train Acc: [0.105636] 
Epoch 2  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.59it/s]
Epoch 3  |  Train Loss : [1.94591]  |  Train Acc: [0.105661] 
Epoch 3  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.75it/s]
Epoch 4  |  Train Loss : [1.94591]  |  Train Acc: [0.105648] 
Epoch 4  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.82it/s]
Epoch 5  |  Train Loss : [1.94591]  |  Train Acc: [0.105624] 
Epoch 5  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.84it/s]
Epoch 6  |  Train Loss : [1.94591]  |  Train Acc: [0.105648] 
Epoch 6  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.83it/s]
Epoch 7  |  Train Loss : [1.94591]  |  Train Acc: [0.105648] 
Epoch 7  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.71it/s]
Epoch 8  |  Train Loss : [1.94591]  |  Train Acc: [0.105648] 
Epoch 8  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.70it/s]
Epoch 9  |  Train Loss : [1.94591]  |  Train Acc: [0.105748] 
Epoch 9  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.43it/s]
Epoch 10  |  Train Loss : [1.94591]  |  Train Acc: [0.105686] 
Epoch 10  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.66it/s]
Epoch 11  |  Train Loss : [1.94591]  |  Train Acc: [0.105648] 
Epoch 11  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.54it/s]
Epoch 12  |  Train Loss : [1.94591]  |  Train Acc: [0.105624] 
Epoch 12  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.81it/s]
Epoch 13  |  Train Loss : [1.94591]  |  Train Acc: [0.105686] 
Epoch 13  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.80it/s]
Epoch 14  |  Train Loss : [1.94591]  |  Train Acc: [0.105711] 
Epoch 14  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.78it/s]
Epoch 15  |  Train Loss : [1.94591]  |  Train Acc: [0.105661] 
Epoch 15  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.97it/s]
Epoch 16  |  Train Loss : [1.94591]  |  Train Acc: [0.105661] 
Epoch 16  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.88it/s]
Epoch 17  |  Train Loss : [1.94591]  |  Train Acc: [0.105661] 
Epoch 17  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:16<00:00, 35.65it/s]
Epoch 18  |  Train Loss : [1.94597]  |  Train Acc: [0.105716] 
Epoch 18  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.75it/s]
Epoch 19  |  Train Loss : [1.94591]  |  Train Acc: [0.105673] 
Epoch 19  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================
Training ...: 100%|██████████| 571/571 [00:15<00:00, 35.93it/s]
Epoch 20  |  Train Loss : [1.94591]  |  Train Acc: [0.105686] 
Epoch 20  |  Valid Loss : [1.94591]  |  Valid Acc: [0.105499] 
================ model saved ================