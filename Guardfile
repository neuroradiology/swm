guard :rspec, cmd: "bundle exec rspec -f documentation" do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { "spec" }
  watch(%w[ spec/spec_helper.rb Gemfile.lock ])  { "spec" }
end

