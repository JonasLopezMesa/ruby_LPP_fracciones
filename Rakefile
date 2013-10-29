desc 'Ejecuta el programa de la clase en lib/fraccion.rb' 
task :bin do
  sh "ruby lib/fraccion.rb"
end

desc 'Ejecuta los tests con --format documentation' 
task :spec do
  sh "rspec -Ilib -Ispec -f d spec/fraccion_spec.rb"
end

desc 'Ejecuta los tests en formato html' 
task :thtml do
  sh "rspec -Ilib -Ispec -f h spec/fraccion_spec.rb"
end