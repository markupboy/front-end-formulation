# Watches haml and scss (compass) files for changes
# compiles all to public directory

guard 'compass' do
  watch(/^.+(\.s[ac]ss)/)
end

guard 'jammit' do
  watch(/^public\/javascripts\/(.*)\.js/)
end

guard 'haml', :input => 'src', :output => 'public' do
  watch(/^.+(\.haml)/)
end
