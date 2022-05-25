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
