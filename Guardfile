guard 'rspec', :version => 2, :cli => '--color --format doc'  do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { |m| "spec/lib/#{m[1]}_spec.rb" }
  watch('spec/spec_helper.rb')  { "spec" }

  watch(%r{^spec/dummy/app/controllers/(.+)_(controller)\.rb$})  { 'spec' }
end

