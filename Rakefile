desc "build the whole site on my local machine"
task :default  do
  sh 'rm -rf _site'
	sh 'compass compile'
	sh 'compass watch &'
	sh 'firefox http://0.0.0.0:4000 &'
  sh 'jekyll --server --auto'
end

