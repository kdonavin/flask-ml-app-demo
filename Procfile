release: python src/create_db.py && python src/build_model.py --out static/model.pkl
web: gunicorn app:app