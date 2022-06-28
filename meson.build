project('Meson vscode configuration generator', 
  version : '0.1')

exename = 'main'

run_command('bash', 'configure',
  env : {'EXENAME' : exename,
         'BUILD_MACHINE_SYS' : build_machine.system()},
  check : true)
