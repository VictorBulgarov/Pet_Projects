{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "86a465d9",
   "metadata": {},
   "source": [
    "# Анализ качества воздуха в Пекине\n",
    "\n",
    "## Введение\n",
    "\n",
    "В этом проекте мы исследовали данные о качестве воздуха в Пекине, сосредоточив внимание на концентрации микрочастиц PM2.5. \n",
    "\n",
    "## Цели проекта\n",
    "\n",
    "- Исследовать динамику изменения уровней PM2.5 во времени.\n",
    "- Оценить влияние различных метеорологических факторов на уровень PM2.5.\n",
    "- Построить и оптимизировать модели для прогнозирования уровней PM2.5 на основе исторических данных.\n",
    "\n",
    "## Основные результаты\n",
    "\n",
    "- `DEWP` (точка росы) является наиболее важным признаком для предсказания уровня PM2.5.\n",
    "- Случайный лес показал наилучшие результаты среди рассмотренных моделей.\n",
    "- Оптимизированная модель на основе случайного леса сохранена для дальнейшего использования.\n",
    "\n",
    "## Инструкции по использованию\n",
    "\n",
    "1. Клонируйте этот репозиторий.\n",
    "2. Загрузите Jupyter Notebook (`beijing_air_quality_analysis.ipynb`) и выполните его, чтобы увидеть полный анализ данных.\n",
    "3. Для использования сохраненной модели загрузите `optimized_random_forest_model.pkl`.\n",
    "\n",
    "## Зависимости\n",
    "\n",
    "- Python 3\n",
    "- Pandas\n",
    "- Numpy\n",
    "- Matplotlib\n",
    "- Seaborn\n",
    "- Scikit-learn\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "9c2e7560",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
