<main id="mobile-app" class="flex-single-col">
<section id="tool-bar" class="flex-col-item">
            <!-- Tool Bar: | Nav tool | breadcrumb | other tool | search tool | -->
            <div class="flex-single-row flex-align-center">
                <section id="nav-tool" class="flex-single-row flex-row-item flex-align-center">
                    <!-- Nav Tool: backward | forward | parent | home -->
                    <span id="nav-parent" class="flex-row-item"><i class="iconfont icon-shang"></i></span>
                    <span id="nav-home" class="flex-row-item"><i class="iconfont icon-a-shouyezhuyefangzi"></i></span>
                </section>
                <section id="breadcrumb-tool" class="flex-single-row flex-row-item flex-rest-item with-border flex-align-center">
                    <!-- breadcrumb: ○ > section 1 > section 2  -->
                    {{ if .IsPage }}
                    {{- partial "breadcrumb.html" .Parent -}}
                    {{ else }}
                    {{- partial "breadcrumb.html" . -}}
                    {{ end }}
                </section>
                <section id="other-tool" class="flex-single-row flex-row-item flex-align-center">
                    <!-- Other tool: Dark/Light | Focus -->
                    <span id="toggler-dark" class="flex-row-item"><i class="iconfont icon-Daytimemode"></i></span>
                    <span id="toggler-layout" class="flex-row-item"><i class="iconfont icon-layout"></i></span>
                </section>
                <section id="search-tool" class="flex-single-row flex-row-item with-border flex-align-center">
                    <span><i class="iconfont icon-sousuo"></i></span>
                    <input id="search-input" placeholder='{{ i18n "search" }}' type="text" />
                </section>
            </div>
        </section>
        </main>
                    
                    

    
    
    



                </section>
                <section id="other-tool" class="flex-single-row flex-row-item flex-align-center">
                    
                    <span id="toggler-dark" class="flex-row-item"><i class="iconfont icon-Daytimemode-fill"></i></span>
                    <span id="toggler-layout" class="flex-row-item"><i class="iconfont icon-layout"></i></span>
                </section>
                <section id="search-tool" class="flex-single-row flex-row-item with-border flex-align-center">
                    <span><i class="iconfont icon-sousuo"></i></span>
                    <input id="search-input" placeholder="Search" type="text">
                </section>
            </div>
        </section>
        <section id="main-body" class="flex-col-item flex-rest-item">
            
            
            <div class="flex-single-row">
                <aside id="body-aside" class="flex-row-item">
                    <section id="widgets">
                        
    
    
        <div id="section-widget" class="widget">
    <span class="widget-header">
        <i class="iconfont icon-jiantouxia widget-fold-control"></i>All Sections
    </span>
    <div class="widget-body" style="user-select: none; height: 0px;">
        <div class="flex-single-col">
            
            <a class="link" href="http://localhost:1313/adult-leagues/">
                <i class="iconfont icon-circle"></i>Adult-leagues
            </a>
            
            <a class="link" href="http://localhost:1313/events/">
                <i class="iconfont icon-circle"></i>Events
            </a>
            
            <a class="link" href="http://localhost:1313/youth-soccer/">
                <i class="iconfont icon-circle"></i>Youth Soccer
            </a>
            
            <a class="link" href="http://localhost:1313/singles/">
                <i class="iconfont icon-circle"></i>Singles
            </a>
            
            <a class="link" href="http://localhost:1313/post/">
                <i class="iconfont icon-circle"></i>My First Post
            </a>
            
        </div>
    </div>
</div>

                    </section>
                    <div class="width-control"></div>
                </aside>
                <div id="body-aside-divider" class="flex-row-item divider-vertical" style="height: auto;"></div>
                <main id="body-content" class="flex-row-item flex-rest-item">
                    <div id="blocks">
                        
    
    
        <div id="profile-block" class="block">
    <style>
       @media only screen and (min-width: 720px) {
        #profile-block {
            max-width: 3000px;
            margin: 5px 5px;
            height: 100%;
            background:var(--shadow-bg-color);
            width: 100%;
            align-items: center;
            
            
        }
        #avatar {
            width: 300px;
            border-radius: 0px;
            object-fit: overflow;
        }
        
           .profile-link {
            margin: 0 0.25em;
            font-size: 22px;
            font-weight: 500;
             
           
            
        }
        }
        
       
       @media only screen and (max-width: 720px) {
       
       
       #profile-block {
            width: 95%;
            
            background:var(--bg-color);
            display: inline-table;
           text-align: center;
           align-items: center;
          margin: 10px 10px;
          margin-bottom: 10%;
       
         border: 1px solid var(--border-color);

}
            
            
            
        
        #avatar {
            width: 50%;
            margin: 10px;
           
        
           align-items: center;
            text-align: center;
            
        }
        .profile-link {
         width: 80%;           
          text-decoration: none; 
          padding: 20px;
          margin: 10px 10px;
          font-size: 30px;
          border: 1px solid var(--shadow-bg-color);
          align-items: center;
         
          }
          
       
           
          
        
         
       
                  
            
            
           
            
        
       

 
    </style>
    
    <section class="flex-single-row flex-align-center">
        <section class="flex-single-col flex-align-center">
            <main class="flex-single-col flex-align-center">
                <img id="avatar" src="/img/logo.png" alt="avatar">
                <h1>
                    A Soccer Directory
                </h1>
                <div>
                    
                    <a class="button-link profile-link" href="http://localhost:1313/adult-leagues/">Adult-leagues</a>
                    
                    <a class="button-link profile-link" href="http://localhost:1313/events/">Events</a>
                    
                    <a class="button-link profile-link" href="http://localhost:1313/youth-soccer/">Youth Soccer</a>
                    
                    <a class="button-link profile-link" href="http://localhost:1313/singles/">Singles</a>
                    
                    <a class="button-link profile-link" href="http://localhost:1313/post/">My First Post</a>
                    
                </div>
                <div>
                    
                    <a class="button-link profile-link" href="tags">tags</a>
                    
                    <a class="button-link profile-link" href="categories">categories</a>
                    
                </div>
            </main>
        </section>
    </section>
    
</div>


                    </div>
                </main>
            </div>
            
            <section id="search-result">
                <div class="flex-single-row">
                    <div id="search-result-mask" class="flex-row-item flex-rest-item"></div>
                    <div id="result-mask-divider" class="flex-row-item divider-vertical" style="height: auto;"></div>
                    <div id="search-result-content" class="flex-row-item">
                        输入回车键，查看搜索结果。
                    </div>
                </div>
            </section>
        </section>
    
