# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit Bayesian Linear and generalized linear Mixed-Effects models Use blmer (blme) With (In) R Software
install.packages("blme")
library("blme")
blmer = read.csv("https://raw.githubusercontent.com/timbulwidodostp/blmer/main/blmer/blmer.csv",sep = ";")
# Estimation Fit Bayesian Linear and generalized linear Mixed-Effects models Use blmer (blme) With (In) R Software
blmer_2 <- blmer(Reaction ~ Days + (Days|Subject), sleepstudy)
summary(blmer_1)
control <- lmerControl(check.conv.grad = "ignore")
blmer_1 <- blmer(Reaction ~ Days + (0 + Days|Subject), sleepstudy, control = control, cov.prior = gamma)
summary(blmer_2)
# Fit Bayesian Linear and generalized linear Mixed-Effects models Use blmer (blme) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished