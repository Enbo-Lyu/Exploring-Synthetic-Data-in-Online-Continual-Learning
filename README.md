## Exploring Synthetic Data in Online Continual Learning

- OCL with Name-Only setting: python3 ocl_nameonly_cifar.py --cuda_device 1 --knn_k 10 --log_file logs/ocl_cifar_real_real_testall_knn10.txt --syn_index 4 --filter1 'saved_data/cifar_train_all_fortest' --filter2 'saved_data/cifar_train_all_fortest' --train_destination '/storage3/enbo/saved_data/combined/cifar_real_real' --test_destination 'saved_data/cifar_train_all_fortest'

- OCL with Fixed Buffer: python3 ocl_fixed_buffer_cifar.py --cuda_device 3 --knn_k 10 --log_file logs/cifar_real_real_knn10_testless.txt --syn_index 3 --filter1 'saved_data/cifar_train_all_fortest' --filter2 'saved_data/cifar_train_all_fortest' --train_destination '/storage3/enbo/saved_data/combined/cifar_real_real' --test_destination 'saved_data/cifar_test100'
