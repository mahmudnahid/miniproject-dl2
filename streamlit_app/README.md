# Streamlit-example

This repository includes an example streamlit app named [bias_map](https://mahmudnahid-miniproje-streamlit-appbias-mapstreamlit-app-1oyjei.streamlit.app/) hosted on streamlit platform.

The app helps you to discover whether language models (in this case DistilBert) are biased towards certain countries! Simply input a sentence which would countain a country name (using * as a country placeholder), and we will look at how the model predictions vary for all possible countries.

Visit the app at: https://mahmudnahid-miniproje-streamlit-appbias-mapstreamlit-app-1oyjei.streamlit.app/

### References
* [RanFeldesh/streamlit-examples](https://github.com/RanFeldesh/streamlit-examples)
* [bias-map](https://github.com/arnaudmiribel/bias-map)

## Usage of this repository

1. Fork or Clone. Forking will be needed to serve the app from Streamlit Cloud
2. To run locally, run `python ./setup/setup.py` from the root folder of the repository (you can first read `/setup/README.md`, or go into the `setup.py` to see what it is doing)
3. Activate the virtual environment for the app you'd like to run
4. Run `streamlit run APP-FILE-NAME` from the root (where e.g. `APP-FILE-NAME=./bias_map/streamlit_app.py`). This will start the app locally on your laptop. To stop the app press `ctrl-c` on `Windows` and `Linux`, or `cmd-c` on Mac in the terminal from which you launched the app. 
5. To serve the app from your own repository, go to [Streamlit Cloud](https://streamlit.io/cloud) and follow the instructions.

## Notes
* The repository includes two apps, each with its own Python package dependencies. The `Streamlit Cloud` service hosts each app independently, with its own Python environment. For multiple apps within a single repository, `Streamlit Cloud` assigns an environment to an app, based on a `requirements.txt` file that is in the app's folder ([docs](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app/app-dependencies)).
