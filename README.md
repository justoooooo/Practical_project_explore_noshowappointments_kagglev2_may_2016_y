# Practical_project_explore_noshowappointments_kagglev2_may_2016_y  
# 探索有哪些重要因素能够帮助我们预测患者是否会按照其挂号预约前往医院就诊  
## 目的
探索有哪些重要因素能够帮助我们预测患者是否会按照其挂号预约前往医院就诊  
## 我将学到什么？  
完成此项目后，你将：  
  
了解典型数据分析过程中所涉及到的所有步骤 轻松提出可用给定数据集回答的问题，并解答这些问题。  

* 了解如何调查数据集中的问题，以及将数据整理成你可以使用的格式  
* 练习传达你的分析结果  
* 能够在 NumPy 和 Pandas 中使用向量化运算，以加快数据分析代码的运行速度  
* 熟悉 Pandas 的 Series 和 DataFrame 对象，它们能使你访问数据更方便  
* 了解如何使用 Matplotlib 生成图形，展示你的发现  

## 数据集的数据字典：  
* PatientId - Identification of a patient
* AppointmentID - Identification of each appointment
* Gender = Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
* DataMarcacaoConsulta = The day of the actuall appointment, when they have to visit the doctor.
* DataAgendamento = The day someone called or registered the appointment, this is before appointment of course.
* Age = How old is the patient
* Neighbourhood = Where the appointment takes place.
* Scholarship = Ture of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia
* Hipertension = True or False
* Diabetes = True or False
* Alcoholism = True or False
* Handcap = True or False
* SMS_received = 1 or more messages sent to the patient. - No-show = True or False.
