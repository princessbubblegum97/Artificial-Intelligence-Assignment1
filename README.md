# Artificial-Intelligence-Assignment1

(v1.3) pkg> add CSV, DataFrames

julia> using DataFrames,CSV,Lasso, MLBase, Random, ConfusionMatrices, Random


julia>File = CSV.read("C:\\Users\\user\\Desktop\\AI 2020\\bank-markeing-campaign\\bank-additional-full.csv")


julia> b=TRAINX = [7,12]

julia>TESTY = Y[123:7,:]


function regularised_crossentropy (A,B, theta, lambda)
j=lenth(B)
k=sigmoid(A * theta)
regularisedlinearregression= (lambda/ (2*j))* sum(theta[2:end].^2)
Z= (1/j) * sum( (-B).*log(j) - (1-y).*log(1-k) ) + regularisedlinearregression
return Z
end


function GRADIENT234 (A, B, theta, lamba, gradient )
j = length (B)
k = sigmoid(A * theta)
gradient  = (1/j) * A' * (k - B)
gradient [2:end] = gradient [2:end] + (lambda/j) * theta[2:end]
return gradient 
end

v(theta::Vector) = cost (A,B, theta, lambda)
l!(theta::Vector, gradient ::Vector)= GRADIENT234(A, B, theta, lambda, gradient)

optimise(v, originaltheta)

function cost_gradient (theta, A, B, lambda )
j = length (B)

return (theta::Array) -> begin 
k=sigmoid(A * theta)
storage [:] = (1/j) * (A'  *  (k .-A)) + (lambda / j) * [0';0[2;end]]
end
end





AGE([56, 57, 37, 40], [56, 45, 59])

function cost(m:: Int::Vector{C} where C<:Real)
  if (theta= 1/2 * n (theta(z)-y)2
)
then (1/2n (theta*x-y)^2



import Pkg
Pkg.add("ConfusionMatrices")

bank-campaign= [1 2 3 4 5 6 7 8 9 10; 56 57 37 40 56 45 59 41 24 25;housemaid services services admin. services services admin. blue-collar technician services; married married married married married married married married single single; basic.4y high.school high.school basic.6y high.school basic.9y professional.course unknown professional.course high.school; no unknown no no no unknown  no unknown no no]
actualmatrix = ConfusionMatrix([data, classlabels= ["Row",  "age", "job", "marital", "education", "default"])
q = reprmime("text/html", actualmatrix)


data= DataFrame= (X=[56, 57, 37, 40, 56, 45, 59, 41], Y=[24, 25, 57, 62, 64, 36, 37, 29])

e = fit(LassoModel, @formla(Y + X), 
StatsModels.TableRegressionModel {LassoModel{LinearModel{GLM.LmResp{Array {Float64,1}},GL

Y + X

coef(e)



//https://juliastats.org/Lasso.jl/stable/lasso/index.html#Lasso-model-fitting-1
//https://juliaobserver.com/packages/ConfusionMatrices
//https://stackoverflow.com/questions/32703119/logistic-regression-in-julia-using-optim-jl
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
