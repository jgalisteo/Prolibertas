source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

# Convertir datos mongoDB en objetos de Ruby
gem 'mongoid', '~> 4.0.1'

# Convierte objetos de nuestros modelos en json
gem 'active_model_serializers', '~> 0.9.3'


gem 'rack-cors', '~> 0.3.1'

# Bootstrap
gem 'bootstrap-sass', '~> 3.3.3'

# Angular
gem 'angular-rails-templates', '~> 0.1.3'
source 'https://rails-assets.org' do
  gem 'rails-assets-angular', '~> 1.3.14'
  gem 'rails-assets-angular-ui-router', '~> 0.2.13'
  gem 'rails-assets-angular-local-storage', '~> 0.1.5'
  gem 'rails-assets-angular-permission', '~> 0.2.0'
end

# Estas gemas sólo se usan en el entorno de desarrollo (development)
group :development do
  # Consola para trabajar en el entorno de desarrollo (development) más bonita
  gem 'pry-rails', '~> 0.3.3'

  # Precarga rails y hace que los tests tarden menos en empezar
  gem 'spring', '~> 1.3.3'
  gem 'spring-commands-rspec', '~> 1.0.4'
end

# Estas gemas sólo se usan en el entorno de test
group :test do
  # Framework de testeo para hacer tests de nuestros modelos y controladores
  gem 'rspec-rails', '~> 3.2.1'

  # Nos da métodos para ayudarnos a testear los modelos hechos con mongoid
  gem 'mongoid-rspec', '~> 2.1.0'

  # Crear datos de ejemplo en la base de datos
  gem 'factory_girl_rails', '~> 4.5.0', group: :development
  # Genera datos falsos que nos van a sevir en nuestras factorías
  gem 'faker', '~> 1.4.3',              group: :development
  # Al terminar de pasarse los tests borra la base de datos
  gem 'database_cleaner', '1.3.0'

  gem 'cucumber-rails', '~> 1.4.2', require: false # Para tests con BDD en las vistas
  gem 'capybara', '~> 2.4.4' # Herramienta para buscar elementos en el DOM durante los tests con cucumber
  gem 'selenium-webdriver', '~> 2.45.0' # Drive para trabajar con javascript en los tests
  gem 'rspec-expectations', '~> 3.2.0' # Expectations de rspec.
end
