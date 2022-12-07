# Global Process

Largely a clone of [Highlander](https://github.com/derekkraan/highlander). This repo adds additional
functionality to Highlander and to help prevent confusion I have given this implimentation a new name.

Ensures there is only a single instance of your process running in an Erlang Cluster*. Global Process
relies heavily on Erlang's `:global` to keep track of processes. Additionally, you can terminate a process
-- `transient` or `temporary` -- for one off tasks that you want to ensure run but then clean themselves up.
