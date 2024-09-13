# BlockHouse Trial

### Functionality 
This is a simple full-stack app made with React/Next.js and Django for data visualization for a variety of different chart types. 

It uses React/Next, Tailwind, Chart.js and Rechart for the UI/UX design, and uses a direct fetch call to populate the data for the charts.

### Running Code
In order to run the app, run an instance of both the Next App and Django together. Then, opening the Next app will display all charts locally on refresh. 

**For Django**: 

1. Change directory into `/blockhouse-backend`

2. Create a virtual environment with `python3 -m venv env` and activate with `source env/bin/activate` on Mac or `.\env\Scripts\activate`

3. Resolve any dependencies if need be with `pip install`

4. Run the app with `python3 manage.py runserver`

**For Next**:

1. Change directory into `/blockhouse-frontend`

2. Run `npm i` and `npm run dev` in the terminal, and follow the link to the web app

Enjoy!
