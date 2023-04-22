# Plotly kod

import plotly.graph_objs as go

data = [go.Bar(
               x = ["Mark", "John", "Daniel","Greg"],
               y = [1000, 1500, 2300, 5000]
)]
layout = {
	'title': 'Salaries with plotly'
}
fig = go.Figure(data, layout)
fig.show()
