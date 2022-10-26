> **CURRICULUM VITAE**
>   
> ## Segura Rosselló Gastón Agustín
> ## Edad: 25 años
> ### Lugar de Nacmiento: Provincia de Catamarca - Capital 
>
> ### Contactos
>
> - **Email:** segurarossello@gmail.com
> - [Linkedin](https://www.linkedin.com/in/gast%C3%B3n-agust%C3%ADn-segura-rossell%C3%B3-a00a74241/)
> 
>
> ____________________________________________________________________________________________
> ### EXPERIENCIA 📝
> - **Trabajos Administrativos en Asesoria General
de Gobierno (desde 2021 hasta la fecha).**

> ____________________________________________________________________________________________
>
> ### EDUCACION FORMAL 📝
> - **Secundario Completo en Titulo Bachiller en Ciencias Sociales y Humanidades (Año : 2015).**
> 
> - **Profesorado en Historia cursando 3° Año.**
> 
> ____________________________________________________________________________________________
>
> ###  EDUCACION COMPLEMENTARIA 📝
>
> - **Curso de Python nivel básico - UTN**
> 
> - **Ingles nivel intermedio**
> 

# frozen_string_literal: true

Gem::Specification.new do |s|
  s.name          = "jekyll-theme-midnight"
  s.version       = "0.2.0"
  s.license       = "CC0-1.0"
  s.authors       = ["Matt Graham", "GitHub, Inc."]
  s.email         = ["opensource+jekyll-theme-midnight@github.com"]
  s.homepage      = "https://github.com/pages-themes/midnight"
  s.summary       = "Midnight is a Jekyll theme for GitHub Pages"

  s.files         = `git ls-files -z`.split("\x0").select do |f|
    f.match(%r{^((_includes|_layouts|_sass|assets)/|(LICENSE|README)((\.(txt|md|markdown)|$)))}i)
  end

  s.required_ruby_version = ">= 2.4.0"

  s.platform = Gem::Platform::RUBY
  s.add_runtime_dependency "jekyll", "> 3.5", "< 5.0"
  s.add_runtime_dependency "jekyll-seo-tag", "~> 2.0"
  s.add_development_dependency "html-proofer", "~> 3.0"
  s.add_development_dependency "rubocop-github", "~> 0.16"
  s.add_development_dependency "w3c_validators", "~> 1.3"
end
