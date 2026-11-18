# Transport compatibility notes

Working notes for the clone-safety documentation effort.

- Context: #1544 reported CI failures right after the git 2.38.1 security fix landed.
- The follow-up tracking issue for this documentation effort is #54321.
- Guard coverage today lives in test/test_command_guards.py; the scenarios described here complement test/test_transport_compat.py.
- Historical anchor: the wording follows the docstring conventions introduced in 2625ed9 and refined later in e4b91a3.
