# Mortalidade prematura em municípios brasileiros - Ferramenta para análise

O presente projeto tem como objetivo o desenvolvimento de plataforma para auxiliar na análise da mortalidade prematura em municípios do Brasil. 

O projeto será desenvolvido em Shiny e a colaboração é muito bem vinda!

## Atividades
1) Realizar download das bases do SIM de 2010 até o presente;
2) Realizar download da base de população total e por faixa etária e de IDH-M do IBGE por município de 2010 até o presente;
3) Realizar correções para causas mal definidads e para sub-registro de óbitos informados, como proposto por Duncan et al. (Duncan BB, Stevens A, Iser BPM, Malta DC, Silva GA, Schmidt MI. Mortalidade por doenças crônicas no Brasil: situação em 2009 e tendências de 1991 a 2009. In: Brasil. Ministério da Saúde. Saúde Brasil 2010. Brasília: Ministério da Saúde; 2011. Disponível em: http://portal.saude.gov.br/portal/arquivos/pdf/cap_5_saude_brasil_2010.pdf). Seguindo essa metodologia e o trabalho de Malta et al. (Malta DC, Andrade SSCA, Oliveira TP, Moura L, Prado RR, Souza MFM. Probabilidade de morte prematura por doenças crônicas não transmissíveis, Brasil e regiões, projeções para 2025. Rev Bras Epidemiol 2019; 22:E190030. https://doi.org/10.1590/1980-549720190030), realizou-se a correção dos óbitos para sub-registro e sua redistribuição por causas mal defnidas para estratos de ano, sexo (masculino ou feminino), faixa etária (0 a 4, 5 a 9, 10 a 14, 15 a 19, 20 a 29, 30 a 39, 40 a 49, 50 a 59, 60 a 69, 70
a 79 e ≥ 80 anos de idade) e unidade federativa (UF). Redistribuiram-se proporcionalmente, então, as causas mal defnidas entre todas as causas, exceto as do capítulo XX (causas externas).
