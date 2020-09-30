title VartikaDadheech;

class About extends Me{

    Present<> getWorkplace()
    {
        return [
            'workplace' => [
                'company' => '404 Not Found',
                'position' => 'Looking for SDE Internships for Summers 2021'
            ]
        ];
    }

    Now<> getTechStack()
    {
        return [
            'languages' => [  '.dart' '.cpp' '.py' '.js' '.cpp' '.java'  ],
            'frameworks' => [  'flutter' 'node' 'django' 'react' ],
            'database' => [  'MySql'  ],
            'softwares' => [  'android-studio' 'vs-code' 'chrome' 'windows-terminal'  ],
            'libraries' => [  'openCV' ],
            'communication' => [  'slack' 'ms-teams' 'google-chat' 'google-meet'  ]
        ];
    }
    
    Past<> getExperience()
    {
        return [
            'workplace' => [
                'company' => 'AnitaB.org Institute for Women and Technology',
                'position' => 'Open Source Developer @ Open Source Hack for beginners'
            ],
            'workplace' => [
                'company' => 'HakinCodes',
                'position' => 'Open Source Flutter delevoper @ Contributor's Hack'
            ]
        ];
    }
    
     Present<> getCommunityExperience()
    {
        return [
            'community' => [
                'company' => 'Google Crowdsource',
                'position' => 'Influencer & Contributor'
            ],
            'community' => [
                'company' => 'UN Girl Up',
                'position' => 'Lead'
            ],
                'community' => [
                'company' => 'Amazon Alexa Jaipur Chapter',
                'position' => 'Core Team Member'
            ],
               'community' => [
                'company' => 'Caerus Infotech',
                'position' => 'Content Lead'
            ],
        ];
    }
    
    Ongoing<> getEducation()
    {
        return [
            'education' => [
                'University' => 'Rajasthan Technical University',
                'degree' => 'Bachelor of Technology',
                'major' => 'Computer Science',
            ]
        ];
    }

    Future<> getGoals()
    {
        return [
            'To contribute to open source.',
            'To build powerful, impactful & helpful communities'
            'To make the world a better place.',
            'To bond with technically grown up minds.',
            'To be happy with life.'
        ];
    }
}





Reach me @ vartikadadheech14nov@gmail.com

