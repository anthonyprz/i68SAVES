# i68SAVES

let quit_flag = 0

cambio de empresa
before menu
    call fshow_camemp()


popup m_archivo

command key (interrupt) m_salir
            exit menu
            DEBAJO DE ↑
command key (control-c)
            call fchange_empresa()

 fmenu_

 al final
call fshow_camemp()


let op_sig = fquit()


########################################################
9520005
9590005   2016

Usabilidad y otras mejoras: interrupt, cambio de empresa, etc
Tratamiento del interrupt con fquit en los casos necesarios, cambio de empresa, eliminar warnings y
 limpieza de los fuentes eliminado comentarios de INCI, DESA,etc
