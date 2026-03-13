# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Flexible Regression Models for Bounded Continuous Responses Use flexreg (FlexReg) With (In) R Software
install.packages("FlexReg")
library("FlexReg")
# Estimation Flexible Regression Models for Bounded Continuous Responses Use flexreg (FlexReg) With (In) R Software
flexreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/flexreg/main/flexreg/flexreg.csv",sep = ";")
flexreg <- flexreg(accuracy.adj ~ iq, data = flexreg, type="FB")
summary(flexreg)
# Flexible Regression Models for Bounded Continuous Responses Use flexreg (FlexReg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished