# Artificial-Intelligence-Assignment1

(v1.3) pkg> add CSV, DataFrames

julia> using DataFrames, CSV, Lasso, MLBase, Random, ConfusionMatrices, Random


julia> File = CSV.read("C:\\Users\\user\\Desktop\\AI 2020\\bank-markeing-campaign\\bank-additional-full.csv")


julia> b = TRAINX = [7,12]

julia> TESTY = Y[123:7,:]


julia> function regularised_crossentropy (real_lambda, number_theta, constantA, constantB)
k = constant_sigmoid(constantA * number_theta)
j = lenth(constantB)
regularisedlinearregression= (real_lambda/ (2*j)) * sum(number_theta[2:end].^2)
Z= (1/j) * sum( (-constantB).*log(j) - (1-y).*log(1-k) ) + regularisedlinearregression
return Z
end


julia> function GRADIENTNAME (constantA, constantB, real_lamba, number_theta, gradientamount )
j = length (constantB)
k = constant_sigmoid(constantA * number_theta)
gradientamount   = (1/j) * constantA' * (k - constantB)
gradientamount [2:end] = gradientamount [2:end] + (real_lambda/j) * number_theta[2:end]
return gradientamount 
end

julia> function(f:Q (m+1)*n),
Q=(1/2*n) * (number_theta * v + y)^2)

julia> v(number_theta::Vector) = regularised_crossentropy (constantA, constantB, number_theta, real_lambda),
l!(number_theta::Vector, gradientamount ::Vector)= GRADIENTNAME(constantA, constantB, number_theta, real_lambda, gradientamount)

julia> optimise(v, originaltheta)

julia> function cost_gradient (number_theta, constantA, constantB, real_lambda )
j = length (constantB)

return (number_theta::Array) -> begin 
k = constant_sigmoid(constantA * number_theta)
storage [:] = (1/j) * (constantA'  *  (k .-constantA)) + (real_lambda / j) * [0';0[2;end]]
end
end

AGE([56, 57, 37, 40], [56, 45, 59])

julia> function regularised_crossentropy(m:: Int::Vector{C} where C<:Real)
  if (number_theta= 1/2 * n (theta(z)-y)2
)
then (1/2n (number_theta*x-y)^2


import Pkg
Pkg.add("ConfusionMatrices")

bank-campaign = [1 2 3 4 5 6 7 8 9 10; 56 57 37 40 56 45 59 41 24 25;housemaid services services admin. services services admin. blue-collar technician services; married married married married married married married married single single; basic.4y high.school high.school basic.6y high.school basic.9y professional.course unknown professional.course high.school; no unknown no no no unknown  no unknown no no]
actualmatrix = ConfusionMatrix([data, classlabels= ["Row",  "age", "job", "marital", "education", "default"])
q = reprmime("text/html", actualmatrix)


julia> data = DataFrame(F = [56, 57, 37, 40, 56, 45, 59, 41], I = [24, 25, 57, 62, 64, 36, 37, 29])

julia> e = fit(LassoModel, @formula(F + I), 
StatsModels.TableRegressionModel {LassoModel{LinearModel{GLM.LmResp{Array {Float64,1}},GL

F + I

julia> coef(e)



//https://juliastats.org/Lasso.jl/stable/lasso/index.html#Lasso-model-fitting-1
//https://juliaobserver.com/packages/ConfusionMatrices
//https://stackoverflow.com/questions/32703119/logistic-regression-in-julia-using-optim-jl
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
