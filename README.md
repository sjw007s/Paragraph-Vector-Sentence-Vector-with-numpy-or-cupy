# Sentence Vector with numpy or cupy
Sentence Vector with numpy or cupy // Sentence Vector without frameworks.

This is a code that implements the Sentence Vector in the paper below with numpy or cupy. Le, Quoc, and Tomas Mikolov. "Distributed representations of sentences and documents." International conference on machine learning. PMLR, 2014. TensorFlow and Pytorch can implement the code, but it makes all the arrays to see how the transformer works in detail. It reproduces weight generation, forward propagation, and back propagation. It was confirmed that 'is' and 'are' are going to a close position. I think it will be useful for those who want to acquire the ability to implement artificial neural networks without the frameworks. The code has been transformed using https://github.com/KONANtechnology/Academy.ALZZA. E-mail: sjw007s@korea.ac.kr

How to run: Run the last code in chap15/NLP_result.ipynb. This code is set up with the cupy library to compute numpy on the GPU. To run it with cpu

Remove 'import cupy as np' from 'chap01/abalone.ipynb' and enable 'import numpy as np'.
Remove 'import cupy as np' from 'chap05/mathutil.ipynb' and enable 'import numpy as np'.
Unnecessary codes are inserted in the middle. Unnecessary operations may be performed. Code is not optimized for computational speed.

아래 논문에서 구현된 Sentence Vector를 numpy 또는 cupy로 구현한 코드입니다. Le, Quoc, and Tomas Mikolov. "Distributed representations of sentences and documents." International conference on machine learning. PMLR, 2014. 텐서플로우와 파이토치로도 충분히 구현이 가능하지만, 구체적으로 내부가 어떻게 동작하는지 보기 위해 배열을 전부 선언하여 가중치 생성, 순전파, 역전파를 전부 구현한 것이 특징입니다. 'is'와 'are'이 가까운 위치로 이동하는 것을 확인하였습니다. 인공신경망을 자유자재로 구현하는 능력을 얻고싶은 분들에게 유용할 것이라 생각합니다. 해당 코드는 https://github.com/KONANtechnology/Academy.ALZZA 을 이용하여 만들었습니다. E-mail: sjw007s@korea.ac.kr

실행방법: chap15/NLP_result.ipynb 에서 맨 마지막 코드를 실행하시면 됩니다. 이 코드는 numpy를 GPU로 연산시키기 위해 사용하는 cupy 라이브러리로 설정되어 있습니다. cpu로 돌리기 위해서는

'chap01/abalone.ipynb' 에서 'import cupy as np' 를 삭제하고 'import numpy as np'를 활성화하세요.
'chap05/mathutil.ipynb' 에서 'import cupy as np' 를 삭제하고 'import numpy as np'를 활성화하세요.
필요없는 코드들이 중간에 삽입되어있습니다. 필요없는 연산이 진행될 수 있습니다. 코드는 계산 속도에 최적화되어 있지 않습니다.
