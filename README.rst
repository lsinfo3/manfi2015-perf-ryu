What's Ryu
==========
Ryu is a component-based software defined networking framework.

Added Processing Timer Module

- Measures processing times of learning switch module.
- Writes statistics to `stats/` directory.
- Contents: processing time within learning switch module
  between packet processing method invocation and before
  leaving method.
- If `packet-out` is generated: write to `stats/po_<$dpid>.txt`
- If `flow-mod` is generated: write to `stats/fm_<$dpid>.txt`


Quick Start
===========

   'git clone git://github.com/lsinfo3/manfi2015-perf-opendaylight.git'
   'cd ryu; python ./setup.py install'
   'PYTHONPATH=. ./bin/ryu-manager ryu/app/simple_switch.py'


Support
=======
Ryu Official site is `<http://osrg.github.io/ryu/>`_.
