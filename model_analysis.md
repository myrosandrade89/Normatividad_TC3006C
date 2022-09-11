# **Análisis de contexto y normatividad | Modelo**

_Fecha de creación: 08/09/2022_
<br> _Autor: Myroslava Sánchez Andrade A01730712_

---

## **Contexto del proyecto**

Análisis de los estados financieros trimestrales históricos de todas las empresas públicas estadounidenses listadas en el New York Exchange y NASDAQ para mejorar la elavoración de modelos de predicción.

Para el análisis y preparación de los datos se hizo uso de paquetes open source como **[pandas](https://pandas.pydata.org/)** y **[numpy](https://numpy.org/)**. Estas librerías son herramientas de manipulación que facilitan el análisis de datos, construidas sobre el lenguaje de programación Python. [pandas, numpy]
Por otro lado, se nos indicaba que el modelo de predicción fuera una regresión lineal. Para este modelado utilizamos la herramientas open source **[statsmodels](https://www.statsmodels.org/stable/index.html)**, este módulo de Python proporciona clases y funciones para la estimación de diferentes modelos estadísiticos. [statsmodel]

---

## **Normativas asociadas al modelado**

GAAP (Generally Accepted Accounting Principles) es el estándar de contabilidad adoptado por la SEC (Securities and Exchange Comission). Este es un conjunto de normas, reglas y procedimientos de contabilidad emitidos por la FASB (Financial Accounting Standards Boards). Las compañías públicas en los Estados Unidos deben se seguir estas normativas al compilar sus estados financieros. [Fernando, J]

El análisis de estados financieros es el proceso de hacer un análisis profundo de estados financieros de una empresa para la toma de decisiones. A pesar de que los estados financieros tienen más importancia para interesados en inversiones, otras personas también se informan y hacen uso de estos. Los estados financieros tienen el propósito de ofrecer un análisis más profundo de los riesgos de los negocios y mejorar la calidad de gestión empresarial y de la competencia. [Britannica]

En cuanto a la publicación de información, la Ley Federal de Protección de Datos Personales en Posesión de los Particulares el artículo 10 establece que no será necesario el consentimiento para el tratamiento de los datos personales cuando: II. Los datos figuren en fuentes de acceso público. [LEY FEDERAL DE PROTECCIÓN DE DATOS PERSONALES EN POSESIÓN DE LOS PARTICULARES]

---

## **Aplicación de normativas en el modelado**

Se hizo un correcto uso de herramientas open source para llevar a cabo el análisis y la predicción, dado un dataset de trimestrales históricos de compañías estadounidenses.

Aún cuando a las personas morales no se les exige apegarse a la GAAP, en el desarrollo del proyecto se buscó seguir normativas establecidas por la GAAP para un correcto análisis financiero. También es importante mencionar que este análisis financiero desarrollado fue realizado con conocimientos adquiridos en clase y corregido con las recomendaciones del Dr. Dorantes. Se aseguró en todo momento de que el análisis fuera el correcto y evitar así la mal información.

Por otro lado, el resultado del modelo se hizo público en la plataforma GitHub. Ya que se trataba de información financiera abierta a todo público, y no se hizo referencia a ninguna persona, la publicación en la plataforma no comete ninguna falta a la Ley Federal de Protección de Datos Personales en Posesión de los Particulares.

---

## **Faltas éticas**

En el caso de que el modelo desarrollado (abierto al público mediante la plataforma GitHub) fuera utilizado para la creación de un índice de apoyo para la inversión con el propósito de ser comercializado limitadamente (a un grupo de personas, sin disponibilidad para competidores, entidades de agregación y público en general), se incurriría en un acto en contra de la reglamentación establecida por la SEC. [SEC]

A pesar de que no se cuenta con una normativa o ley establecida para el correcto análisis de estados financieros, tenemos la responsabilidad como profesionistas de no incurrir a la malinformación.

---

## **Conclusión**

Primero que nada, es muy importante entender y analizar el contexto del problema y lo que planeamos ejecutar. Esto también está compuesto por todas las normas y leyes que se aplican a dicho contexto.
<br>Es importante que antes de hacer uso de los datos, entendamos estos y nos aseguremos de conocer cómo deben de ser utilizados y tratados estos. En algunos casos se llegan a romper normas sin malicia, pero también forma parte de nuestra responsabilidad el cuidar todos estos aspectos.

---

### **Referencias**

- NumPy. (s/f). "NumPy documentation". NumPy. Recuperado el 9 de septiembre del 2022 del sitio web: https://numpy.org/doc/stable/

- pandas. (s/f). "pandas". Pandas. Recuperado el 9 de septiembre del 2022 del sitio web: https://pandas.pydata.org/

- statsmodel. (s/f). "statistical models, hypothesis tests, and data exploration". statsmodel. Recuperado el 9 de septiembre del 2022 del sitio web: https://www.statsmodels.org/stable/index.html

- Fernando, J. (2022). "GAAP: Understanding it and the 10 key principles". Investopedia. Recuperado el 9 de septiembre del 2022 del sitio web: https://www.investopedia.com/terms/g/gaap.asp

- Britannica, The Editors of Encyclopaedia. (2022). "Financial statement". Encyclopedia Britannica. Recuperado el 9 de septiembre del 2022 del sitio web: https://www.britannica.com/topic/financial-statement

- LEY FEDERAL DE PROTECCIÓN DE DATOS PERSONALES EN POSESIÓN DE LOS PARTICULARES. Artículo 10. 5 de julio del 2010.

- SEC. (s/f). "What we do". U.S. SECURITIES AND EXCHANGE COMISSION. Recuperado el 9 de septiembre del 2022 del sitio web: https://www.sec.gov/about/what-we-do
