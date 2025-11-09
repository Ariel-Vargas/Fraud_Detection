# Detección de Fraude de transacciones bancarias

Integrantes:
- Ariel Vargas
- Domenica Bolaños

## Introducción 

Los fraudes en transacciones bancarias constituyen un delito financiero significativo y creciente, especialmente en la era de la banca digital. Se definen como un conjunto de estafas y actividades ilícitas cuyo objetivo principal es obtener fondos, información confidencial, o acceso no autorizado a las cuentas de clientes e instituciones financieras. Estos actos provocan grandes pérdidas económicas tanto a individuos como a empresas a nivel global.

## Dataset:
Se utilizó un dataset de Kaggle Credit Card Fraud Detection, donde se tiene las siguientes variables:
- Time: Números de segundos entre realización de la transacción
- V1 - V28: Características de las transacciones con transformadas en PCA
- Amount: Cantidad realizada en la transacción
- Class: Determina si la transacción es fraude o Legítima (0: Legítima, 1: Fraude)

## Objetivo
Realizar un modelo de Machine Learning para detectar si las proximas transacciones serían fraudes o legítimas.

## Descripción del problema

### Preprocesamiento
Se realizó un análisis del dataset para verificar su información, tipo de datos, etc. Además una visualización del desbalance de clase entre transacciones fraudulentas y legítimas.
Para manejar este problema de desbalance, se realizó peso de clase para dar más atención a los datos minoritarios que a los mayoritarios, es decir a los datos fraudulentos que los legítimos.
Además, para empezar con el entrenamiento del modelo, se realizó 

### Entrenamiento

