---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: redcharlie-unsplash.jpg
widget1:
  title: "Podcast"
  url: '/podcast/'
  image: podcast_302.jpg
  text: 'Los mejores podcast para que no te pierdas nada de la actualidad más "espaciotrastornada". '
widget2:
  title: "Revista"
  url: '/revistas/'
  text: 'Cada mes (más o menos) pubicamos una revista digital recopilando nuestras salidas nocturnas, consejos y recursos de utilidad. Hecha a base de mucho amor y pinchos de tortilla :)'
  image: magazine_302.jpg
widget3:
  title: "Recursos"
  url: '/recursos/'
  image: resources_302.jpg
  text: '¿Buscando una app para reconocer las estrellas? ¿Dónde encontrar cuándo es visible la ISS, o el próximo lanzamiento de SpaceX?... Aquí te dejamos una lista de recursos de lo más variado .'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
# callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
