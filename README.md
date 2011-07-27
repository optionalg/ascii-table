# ASCII table generator

### Usage

    @at = AsciiTable.new
    @at.header = true # Uses first row as a header. Default: false
    @at.lineup = true # Draws lines to separate rows. Default: false
    @at.generated = false # Shows that importune "generated by" footer. Default: true
    @at.data = [['Orange', 'Green', 'Yello', 'Blue', 'Pink'], [1, 2, 3, 4, 5], [6, 7, 8, 9, 10], [11, 12, 13, 14, 15], [16, 17, 18, 19, 20]]
    puts @at.build

### Example

         ______________________________________
        | Orange | Green | Yello | Blue | Pink |
        |========|=======|=======|======|======|
        | 1      | 2     | 3     | 4    | 5    |
        |--------|-------|-------|------|------|
        | 6      | 7     | 8     | 9    | 10   |
        |--------|-------|-------|------|------|
        | 11     | 12    | 13    | 14   | 15   |
        |--------|-------|-------|------|------|
        | 16     | 17    | 18    | 19   | 20   |
        |--------------------------------------|
        |         Generated by ascii-table gem |
        |______________________________________|

### Contributing to ascii-table
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

### Copyright

Copyright (c) 2011 Gregory Eremin. See LICENSE.txt for
further details.
