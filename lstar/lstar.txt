# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Logistic Smooth Transition Autoregressive Regression (LSTAR) Model for Time Series Data Use lstar With (In) R Software
install.packages("tsDyn")
library("tsDyn")
lstar = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lstar/main/lstar/lstar.csv",sep = ";")
# Estimation Logistic Smooth Transition Autoregressive Regression (LSTAR) Model for Time Series Data Use lstar With (In) R Software
lstar <- lstar(lstar$log10_wpi, m=1,  include="none")
summary(lstar)
# Logistic Smooth Transition Autoregressive Regression (LSTAR) Model for Time Series Data Use lstar With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished