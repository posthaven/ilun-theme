
desc 'Compile the SCSS'
task :compile do
  exec 'scss', '--sourcemap=none', 'src/blog.scss:assets/blog.css'
end

desc 'Watch the SCSS files and compile on change'
task :watch do
  exec 'scss', '--watch', '--sourcemap=none', 'src/blog.scss:assets/blog.css'
end

task default: :compile
