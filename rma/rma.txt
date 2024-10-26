# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fixed-Effects and Random-Effects Models in Meta-Analysis Use rma (metafor) With (In) R Software
install.packages("metafor")
library("metafor")
rma = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rma/main/rma/rma.csv",sep = ";")
# Estimation Fixed-Effects and Random-Effects Models in Meta-Analysis Use rma (metafor) With (In) R Software
# Fixed-Effects Model
rma_fixed <- rma(yi, vi, data=rma, method="FE")
rma_fixed
# Random-Effects Model
rma_random <- rma(yi, vi, data=rma)
rma_random
# Fixed-Effects and Random-Effects Models in Meta-Analysis Use rma (metafor) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished