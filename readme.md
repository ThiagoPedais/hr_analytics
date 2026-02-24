# 📊 HR Analytics — Employee Attrition Analysis

## 📌 Contexto
A rotatividade de funcionários (attrition) é um dos principais desafios na área
de Recursos Humanos, impactando custos, produtividade e continuidade
organizacional. Este projeto utiliza dados de RH para analisar padrões de
desligamento e identificar fatores associados à saída de colaboradores.

---

## 🎯 Objetivo do Projeto
Compreender os principais fatores relacionados ao desligamento de funcionários,
explorando aspectos demográficos, profissionais, remuneratórios,
comportamentais e de histórico de carreira, a fim de gerar insights que apoiem
estratégias de retenção.

---

## 🗂️ Conjunto de Dados
**Dataset:** HR Analytics – Employee Attrition  
**Total de registros:** 1.470 funcionários  

### Principais variáveis analisadas:
- **Attrition:** Indicador de desligamento (Yes / No)
- **Demográficas:** Age, Gender, MaritalStatus, Education, EducationField
- **Profissionais:** Department, JobRole, JobLevel, BusinessTravel, OverTime
- **Remuneração:** MonthlyIncome, PercentSalaryHike, StockOptionLevel
- **Satisfação e Engajamento:** JobSatisfaction, WorkLifeBalance, JobInvolvement
- **Histórico de Carreira:** YearsAtCompany, YearsWithCurrManager,
  YearsSinceLastPromotion

Variáveis constantes ou identificadores (EmployeeNumber, EmployeeCount,
StandardHours) foram desconsideradas por não agregarem valor analítico.

---

## 🔍 Metodologia
1. Carregamento e entendimento inicial dos dados  
2. Validação de tipos, valores nulos e estatísticas descritivas  
3. Conversão de variáveis categóricas e ordinais para tipos adequados  
4. Análise exploratória (EDA)  
5. Comparações entre grupos (Attrition = Yes vs No)  
6. Aplicação de testes estatísticos (Qui-quadrado e Teste t de Welch)  
7. Interpretação dos resultados com foco em negócio  

---

## 📈 Principais Análises
- Distribuição geral do desligamento (attrition)
- Perfil demográfico e formação
- Desempenho por departamento e cargo
- Impacto de horas extras e frequência de viagens
- Relação entre remuneração e desligamento
- Satisfação, engajamento e work-life balance
- Histórico de carreira e relação com liderança

---

## 💡 Principais Insights
- Funcionários mais jovens (18–24 anos) apresentam maior taxa de desligamento.
- Departamentos de Vendas e Recursos Humanos concentram os maiores índices de
  rotatividade, com destaque para o cargo de Sales Representative.
- Funcionários que realizam horas extras ou viajam frequentemente apresentam
  taxas de desligamento significativamente mais altas.
- Menores níveis de satisfação, engajamento e equilíbrio entre vida pessoal e
  profissional estão associados a maior attrition.
- Funcionários que se desligaram possuem, em média, salários significativamente
  menores.
- Menor tempo de empresa e menor tempo com o gestor atual estão associados a
  maiores taxas de desligamento.

---

## 🧠 Conclusão
Os resultados indicam que o desligamento de funcionários é um fenômeno
multifatorial, influenciado por características demográficas, condições de
trabalho, remuneração, fatores comportamentais e histórico de carreira. Os
insights reforçam a importância de estratégias integradas de retenção, com foco
em início de carreira, cargos comerciais, gestão de horas extras, liderança e
engajamento.

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

📌 *Projeto desenvolvido para fins de portfólio em Análise de Dados / HR Analytics.*