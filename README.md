# Estadística Bayesiana y Programación Probabilística
## O cómo aprendí a dejar de preocuparme y amar la incertidumbre

Plática para el Data Day 2017 por Adolfo Martínez.

- Los slides en `slides_xaringan.html` o `slides.pdf`
- El .Rmd en `slides_xaringan.Rmd`
- Ejemplo funcional de python en `ejemplo.ipynb`

### Cómo ver
Clona el repositorio y abre en algún browser `slides_xaringan.html` o abrir el PDF: `slides.pdf`

### Cómo reconstruir el ejemplo
Activa tu virtualenv o pyenv con python 3.5.2 y

```{python}
    pip install -r requirements.txt
    jupyter notebook
```
Abre `ejemplo.ipynb` y corre todos los chunks

### Cómo reconstruir la presentación
Instala [xaringan](https://github.com/yihui/xaringan), abre `slides_xaringan.Rmd` en RStudio y ve a File -> Knit Document

Para construir el PDF, usar [decktape](https://github.com/astefanutti/decktape) con el comando remark

Referencias:
- [*Bayesian Reasoning and Machine Learning*](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/090310.pdf) - David Barber 
- [*Bayesian Methods for Hackers*](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Cameron Davidson-Pilon
- [*Probabilistic Programming*](http://blog.fastforwardlabs.com/2017/01/30/the-algorithms-behind-probabilistic-programming.html) - Fast Forward Labs
