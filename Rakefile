desc "Publish site to S3"
task :publish do
  system 'bundle exec jekyll build'
  system 'bundle exec s3_website push'
end
