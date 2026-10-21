team = {
    'name': 'Walmart Hurricane Project Team',

    'members': [
        {'name': 'Emma', 'github': 'emmakelly7'},
        {'name': 'Liv', 'github': 'oliviadellaglio'},
        {'name': 'Caroline', 'github': 'cetracey'},
        {'name': 'Anastacia', 'github': 'tqd3pz'},
    ],

    'goals': {
        'good_result': (
            'All members aim to earn an A by completing accurate, '
            'well-organized work on time. Everyone will contribute '
            'to the analysis and final presentation.'
        ),

        'what_each_person_wants': (
            'All members want to improve their skills in data '
            'cleaning, mapping, grouping, analysis, and teamwork '
            'using GitHub and Google Colab.'
        ),

        'time_limits': (
            'All members will attend class for the next two weeks '
            'to complete group work. We will meet during Wednesday '
            'class and, if needed, after class from 2:00-3:30 PM.'
        ),

        'what_to_avoid': (
            'Missing deadlines, unequal participation, poor '
            'communication, inaccurate analysis, and last-minute '
            'work that prevents adequate review.'
        ),
    },

    'roles': {
        'cleaning + decision log': {
            'owner': 'Caroline',
            'backup': 'Anastasia'
        },

        'weather API + join': {
            'owner': 'Liv',
            'backup': 'Emma'
        },

        'analysis Q1-Q5': {
            'owner': 'Emma',
            'backup': 'Caroline'
        },

        'charts + presentation': {
            'owner': 'Anastasia',
            'backup': 'Liv'
        },
    },

    'question_owners': {
        'Q1 demand surge': {
            'owner': 'Emma',
            'reviewer': 'Caroline'
        },

        'Q2 SKU consolidation': {
            'owner': 'Caroline',
            'reviewer': 'Anastasia'
        },

        'Q3 weather correlation': {
            'owner': 'Liv',
            'reviewer': 'Emma'
        },

        'Q4 stores and geography': {
            'owner': 'Anastasia',
            'reviewer': 'Emma'
        },

        'Q5 signal or artifact': {
            'owner': 'Emma',
            'reviewer': 'Liv'
        },
    },

    'repo_url': 'https://github.com/oliviadellaglio/ds2002-walmart-midterm',

    'notebook_owner_this_week': 'Emma',

    'meeting_time': (
        'Wednesday during class, with a proposed additional '
        'meeting from 2:00-3:30 PM if necessary.'
    ),

    'channel': (
        'Group chat. All members will remain responsive. '
        'Proposed response expectation: within 24 hours.'
    ),

    'how_we_decide': (
        'We will discuss disagreements as a group, consider '
        'the evidence, and aim for consensus. If consensus '
        'cannot be reached, we will use a majority vote.'
    ),

    'if_someone_goes_quiet': (
        'We will contact the member through the group chat '
        'and follow up individually if necessary. If the '
        'issue continues, we will redistribute urgent work '
        'and consult the instructor if needed.'
    ),
}

def find_todos(obj, path=()):
    if isinstance(obj, dict):
        return [t for k, v in obj.items() for t in find_todos(v, path + (k,))]
    if isinstance(obj, list):
        return [t for i, v in enumerate(obj, 1) for t in find_todos(v, path + (f'#{i}',))]
    return [' > '.join(path)] if str(obj).strip() in ('', 'TODO') else []

unfilled = find_todos(team)
if unfilled:
    print(f'{len(unfilled)} items still unfilled. First few:')
    for item in unfilled[:8]:
        print('  -', item)
else:
    print('nothing unfilled -- charter is complete')
