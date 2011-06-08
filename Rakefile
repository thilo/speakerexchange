desc "build the whole site on my local machine"
task :build  do
  sh 'rm -rf _site'
	sh 'compass compile css/'
	sh 'compass watch css/ &'
	sh 'firefox http://0.0.0.0:4000 &'
  sh 'jekyll --server --auto'
end

