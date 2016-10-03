## Usage

Install missing dependencies:

    bundle install

Compile the site:

    bundle exec nanoc

Serve the compiled site at http://localhost:3000:

    bundle exec nanoc view

Automatically recompile the site upon filesystem writes to files that may
change the output:

    bundle exec guard
