메모)

AutoEncoder는 차원 축소 -> 확장해서 복원시키는 느낌이라면 // 

Transformer의 Encoder와 Decoder는

Encoder에서 각 단어에 대한 표헌벡터를 만들고 (문맥 반영o)

Decoder에서 그 표현벡터를 이용한 다른 task를 수행할 수 있도록 만드는 것 (번역 등) 

(Decoder의 Multi head attention부분에서 encoder의 결과물(표현벡터)(ex.한국어)과 decoder 이전층의 결과물(ex.프랑스어)을 함께 이용하면서 번역과 같은 task를 수행할 수 있음)

