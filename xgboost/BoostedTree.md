# 提升树简介
## 模型和参数
  yhat = sum(f) _{1,n}_    
  cost = sum(loss(yhat,y)) _{1,n}_ +sum(complexity(f)) _{1,k}_  
  complexity(ft) = gamma\*T(叶子个数)+0.5\*lambda\*sum(w\*\*2(叶子的参数)) _{1,T}_
