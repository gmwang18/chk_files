dm=hf.init_guess_by_chkfile('guess/Fe.chkfile')

hf.chkfile='Fe.chkfile'

en=hf.kernel(dm)
