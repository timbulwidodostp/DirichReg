# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fitting a Dirichlet Regression Use DirichReg (DirichletReg) With (In) R Software
install.packages("DirichletReg")
library("DirichletReg")
DirichReg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/DirichReg/main/DirichReg/DirichReg.csv",sep = ";")
# Estimation Fitting a Dirichlet Regression Use DirichReg (DirichletReg) With (In) R Software
AL <- DR_data(DirichReg[,1:3])
DirichReg <- DirichReg(AL ~ depth + I(depth^2), DirichReg)
summary(DirichReg)
# Fitting a Dirichlet Regression Use DirichReg (DirichletReg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished