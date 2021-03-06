# 0.1.2
  * Always converting actual attribute names to string before checking for existence.

# 0.1.1
  * Explicitly require rspec/expectations.

# 0.1.0
  * Include remarkable/active_record within the gem.

# 0.0.9
  * Better support for conditions in validate_presence_of.

# 0.0.8
  * Feature: Support options for validate_uniqueness_of.

# 0.0.6
  * Bug: Do not crash when validate_numericality_of is used without any options.

# 0.0.5
  * Feature: Introducing validate_numericality_of matcher.

# 0.0.4
  * Feature: Introducing validate_presence_of, validate_uniqueness_of and validate_inclusion_of matchers.

# 0.0.3
  * Fix: Do not cache the with clause for subsequent matches.

# 0.0.2
  * Fix: Do not crash when the with clause is missing.

# 0.0.1
  * Fix: Requiring rspec explicitly to eliminate 'uninitialized constant RSpecAttributeMatchers::RSpec' on running rake tasks.

# 0.0.0
  * Feature: Introducing rspec_attribute_matchers, a simple way of writing specs for activemodel attributes.
