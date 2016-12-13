# fecha_nombre

write.csv(q6, file = paste("q6","_", format(Sys.time(), "%y-%m-%d_%H-%M"),".csv", sep = ""))

tiff(filename = paste("StCO2.dico_violin","_", format(Sys.time(), "%y-%m-%d_%H-%M"),".tiff", sep = ""), res = 200, width = 2100, height = 2000)    
print(StCO2.dico_violin)
dev.off()
graphics.off()
