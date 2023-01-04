# schizo

<< mkdir results >>

python analyze.py

В результате исследований показано, что анализ на основе искусственного интеллекта молекулярных маркеров иммуновоспаления в сыворотке человека позволяет вычислять вероятностные оценки заболевания пациентом шизофренией. Такие предсказания могут служить как основой для объективного независимого диагноза, так и дополнительным признаком, взятым доктором во внимание. 
 
В результате исследований построен и обучен ряд моделей с разными архитектурами: логистическая регрессия, глубокая нейронная сеть и деревья решений. Созданные модели позволяют по значениям маркеров классифицировать тестируемый набор признаков нового пациента, то есть определить их принадлежность к одному из двух классов: пациенты с шизофренией и группа здоровых лиц. Все три подхода демонстрируют близкие результаты и служат взаимной проверкой своих ответов. 

Используя методику независимых тестовых выборок, было показано, что нейронная сеть позволяет идентифицировать по маркерам шизофрению у пациентов с вероятностью 81±9%, и предсказывать ложный диагноз для здоровых лиц с вероятностью 42±9%.
