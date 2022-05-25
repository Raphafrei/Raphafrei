<div align="center">
  <a href="https://github.com/raphaelfrei">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=raphaelfrei&layout=compact&langs_count=8&theme=dracula"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=raphaelfrei&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

```cs    
using GitHub;
using LinkedIn;

namespace RaphaelFrei{

    public class AboutMe{

        public string getCurrentWorkplace(){
            return [
                'workplace' => [
                    'company'   => 'Adient PLC',
                    'position'  => 'Intern/Student',
                    'role'      => 'Software Developer'
                ]
            ];

        }

        public string getLanguages(){
            return [
                C::class,
                CSharp::class,
                Python::class,
                OpenEdgeABL::class,
                PHP::class,
                HTML::class,
                JavaScript::class,
                ActionScript::class,
                Swift::class
            ];
        }
    }
}
```
