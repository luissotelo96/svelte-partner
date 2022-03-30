<script>
    import Svg from "./Svg.svelte"
    import Home from "../home/Home.svelte"
</script>

<Svg />

<div class="d-flex flex-column flex-shrink-0 border" style="width: 5.5rem; float: left;">
    <a href="/" class="d-block p-3 link-dark text-decoration-none" title="Icon-only" data-bs-toggle="tooltip" data-bs-placement="right">
        <img src="https://github.com/mdo.png" alt="mdo" width="60" height="60" class="rounded-circle"/>
        <span class="visually-hidden">Icon-only</span>
    </a>
    <ul class="nav nav-pills nav-flush flex-column mb-auto text-center">
        <li class="nav-item">
        <a href="#" class="nav-link py-3" aria-current="page" title="Home" data-bs-toggle="tooltip" data-bs-placement="right">
            <svg class="bi" width="24" height="24" role="img" aria-label="Home"><use xlink:href="#home"/></svg>    
            <span>Inicio</span>        
        </a>
        </li>
        <li>
            <a href="#" class="nav-link py-3" title="Customers" data-bs-toggle="tooltip" data-bs-placement="right">
                <svg class="bi" width="24" height="24" role="img" aria-label="Customers"><use xlink:href="#people-circle"/></svg>
                <span>Social</span>  
            </a>            
        </li>
        <li>
        <a href="#" class="nav-link py-3" title="Dashboard" data-bs-toggle="tooltip" data-bs-placement="right">
            <svg class="bi" width="24" height="24" role="img" aria-label="Dashboard"><use xlink:href="#speedometer2"/></svg>
            <span>Laboral</span>  
        </a>        
        </li>
        <li>
        <a href="#" class="nav-link py-3 border-bottom" title="Products" data-bs-toggle="tooltip" data-bs-placement="right">
            <svg class="bi" width="24" height="24" role="img" aria-label="Products"><use xlink:href="#grid"/></svg>
            <span>Cool</span>  
        </a>        
        </li>
        <li>
            <a href="#" class="nav-link py-3" data-bs-toggle="tooltip" data-bs-placement="right">
                <img src="img/WebHelpLogo2.png" alt="mdo" width="50" height="50" class="rounded-circle" />                
            </a>        
        </li>
        <li>
            <a href="#" class="nav-link py-3 border-bottom" data-bs-toggle="tooltip" data-bs-placement="right">
                <img src="img/WebHelpUniversityLogo.png" alt="mdo" width="50" height="50" class="rounded-circle" />                
            </a>        
        </li>
        <li>
            <a href="#" class ="nav-link py-3" data-bs-toggle="tooltip" data-bs-placement="right"></a>
            <button type="button" class="btn btn-primary rounded-pill" style="background-color: #CC3262;">Referir</button>
        </li>
        <li>
            <a href="#" class ="nav-link py-3" data-bs-toggle="tooltip" data-bs-placement="right"></a>
            <button type="button" class="btn btn-primary rounded-pill" style="background-color: #CC3262;">Ofertas</button>
        </li>
        <li>
            <a href="#" class="nav-link py-3 border-bottom" data-bs-toggle="tooltip" data-bs-placement="right">
                <img src="img/Birthay.png" alt="mdo" width="50" height="50" class="rounded-circle" />                
            </a> 
        </li>        
    </ul>    
</div>

<Home />

<style>
    .bi {
        vertical-align: -.125em;
        pointer-events: none;
        fill: currentColor;
    }
    
    .nav-flush .nav-link {
        border-radius: 0;
    } 

</style>