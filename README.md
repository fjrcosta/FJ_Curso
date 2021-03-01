FJ_Curso. Curso em Swirl como parte das atividades de Tópicos de modelagem estatística

library(swirl)
temp <- tempfile()
download.file("https://github.com/fjrcosta/FJ_Curso/raw/main/FJ_Curso.swc", temp)
install_course(swc_path = temp)
