source "https://rubygems.org"
# Hola! Aquí es donde manejas cual versión Jekyll es usada para procesar.
# Cuando quieres usar una versión diferente, cámbialo abajo, guarda el
# archivo y ejecuta `bundle install`. Ejecuta Jekyll con `bundle exec`, así:
#
#     bundle exec jekyll serve
#
# Esto ayudará asegurar que la versión apropiada de Jekyll se ejecute.
# ¡Feliz Jekjecución!
# gem "jekyll", "~> 4.3.3"
# Este es el tema defacto para sitios Jekyll nuevos. Podrías cambiar esto a cualquier cosa que tú quieras.
# gem "minima", "~> 2.5"
# Si tú quieres usar GitHub Pages, quita "gem "jekyll"" de arriba y
# descomenta la linea de abajo. Para mejorizar, dale `bundle update github-pages`.
gem "github-pages", "~> 228", group: :jekyll_plugins
# Si tienes cualquier plugins, ¡ponlos aquí!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jemoji', '~> 0.12.0'
  gem 'dotenv', '~> 2.8', '>= 2.8.1', groups: [:development, :test]
end

# Windows y JRuby no incluyen archivos zoneinfo, así que alpaca la gema
# tzinfo-data y librería associada.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Acelerador de desempeño para vigilar directorios en Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Traba la gema `http_parser.rb` a `v0.6.x` en los montajes de JRuby ya que versiones más nuevas de la gema
# no tienen una contraparte Java.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
